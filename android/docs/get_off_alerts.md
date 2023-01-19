## Permissions

You first need to ask user's to allow the permissions below:
````
android.Manifest.permission.ACCESS_FINE_LOCATION,
android.Manifest.permission.ACCESS_BACKGROUND_LOCATION
````  

## Get off alerts enable/disable state for a trip

You can use [`GetOffAlertCache`](tripkit-android/com.skedgo.tripkit.routing/-get-off-alerts-cache/index.md) to save get off alerts feature enable/disable state (or you can use your own) by your trip identifier.

__Initialize class with application context__

````
GetOffAlertCache.INSTANCE.init(applicationContext);
````

__Set get off alert state for a trip__

````
fun setTripAlertOnState(tripUuid: String, onState: Boolean)
````

> __Parameters__

| Name  | Type | Required | Description |
| ------------- | ------------- | ------------- | ------------- | 
| tripUuid | String  | Yes | Your trip unique identifier |
| onState | Boolean | Yes | enable/disable state |

> __Sample__

````
GetOffAlertCache.setTripAlertOnState("your_trip_identifier", true)
````

__Get get off alert state for a trip__

````
fun isTripAlertStateOn(tripUuid: String): Boolean
````

> __Parameters__

| Name  | Type | Required | Description |
| ------------- | ------------- | ------------- | ------------- | 
| tripUuid | String  | Yes | Your trip unique identifier |

> __Response__

Boolean - the enable/disable state of get off alert for the specified trip



## [`GeoLocation`](tripkit-android/com.skedgo.tripkit.routing/-geolocation/index.md)

This class handles the creation and removal of geofences for the trip segments when alerts are enabled

__Add receiver on your project's Manifest.xml__
````
<receiver
    android:name=".routing.GeofenceBroadcastReceiver"
    android:enabled="true"
    android:exported="true">
    <intent-filter>
        <action android:name="com.skedgo.tripkit.routing.GeofenceBroadcastReceiver.ACTION_GEOFENCE_EVENT" />
    </intent-filter>
</receiver>
````

__Initialize class with application context__

```` java
GeoLocation.INSTANCE.init(applicationContext)
````

```` kotlin
GeoLocation.init(applicationContext)
````

__Create Geofences using [`Geofence`](tripkit-android/com.skedgo.tripkit.routing/-geofence/index.md) from [`TripSegment`](tripkit-android/com.skedgo.tripkit.routing/-trip-segment/index.md)__

````
fun createGeoFences(geofences: List<Geofence>)
````

> __Parameters__

| Name  | Type | Required |
| ------------- | ------------- | ------------- |
| geofences | List<[`Geofence`](tripkit-android/com.skedgo.tripkit.routing/-geofence/index.md)>  | Yes |


> __Sample__
````
trip.segments?.mapNotNull { it.geofences }?.flatten()?.let { geofences ->
                        GeoLocation.createGeoFences(
                                geofences.map { geofence ->
                                    geofence.computeAndSetTimeline(trip.endDateTime.millis)
                                    geofence
                                }
                        )
                    }
````

__Clear geofences__
````
fun clearGeofences()
````


## Alert for trip start

__Add receiver on your project's Manifest.xml__
````
<receiver
    android:name=".routing.TripAlarmBroadcastReceiver"
    android:enabled="true"
    android:exported="true"/>
````

When get off alert is enabled for your trip, create an [`AlarmManager`](https://developer.android.com/reference/android/app/AlarmManager) instance using your [`Trip`](tripkit-android/com.skedgo.tripkit.routing/-trip/index.md)'s start [`segment`](tripkit-android/com.skedgo.tripkit.routing/-trip-segment/index.md)

````
trip.segments.minByOrNull { it.startTimeInSecs }?.let { startSegment ->
    val alarmManager = context.getSystemService(Context.ALARM_SERVICE) as AlarmManager
    val startSegmentStartTimeInSecs = startSegment.startTimeInSecs

    val alarmIntent = Intent(context, TripAlarmBroadcastReceiver::class.java)
    alarmIntent.putExtra(TripAlarmBroadcastReceiver.ACTION_START_TRIP_EVENT, true)
    alarmIntent.putExtra(TripAlarmBroadcastReceiver.EXTRA_START_TRIP_EVENT_TRIP, Gson().toJson(trip))

    var pendingIntent = PendingIntent.getBroadcast(context, 0, alarmIntent, 0)
}
````

then set the alarm trigger by time in milliseconds you want before the start of your [`Trip`](tripkit-android/com.skedgo.tripkit.routing/-trip/index.md)'s start [`segment`](tripkit-android/com.skedgo.tripkit.routing/-trip-segment/index.md)

````
alarmManager.set(
    AlarmManager.RTC_WAKEUP,
    (TimeUnit.SECONDS.toMillis(startSegmentStartTimeInSecs) - TimeUnit.MINUTES.toMillis(5)),
    pendingIntent
)
````
