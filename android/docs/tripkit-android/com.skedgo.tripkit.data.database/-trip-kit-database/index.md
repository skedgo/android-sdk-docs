[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database](../index.md) / [TripKitDatabase](./index.md)

# TripKitDatabase

`abstract class TripKitDatabase : RoomDatabase`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripKitDatabase()` |

### Functions

| Name | Summary |
|---|---|
| [bikePodDao](bike-pod-dao.md) | `abstract fun bikePodDao(): `[`BikePodDao`](../../com.skedgo.tripkit.data.database.locations.bikepods/-bike-pod-dao/index.md) |
| [carParkDao](car-park-dao.md) | `abstract fun carParkDao(): `[`CarParkDao`](../../com.skedgo.tripkit.data.database.locations.carparks/-car-park-dao/index.md) |
| [carPodDao](car-pod-dao.md) | `abstract fun carPodDao(): `[`CarPodDao`](../../com.skedgo.tripkit.data.database.locations.carpods/-car-pod-dao/index.md) |
| [onStreetParkingDao](on-street-parking-dao.md) | `abstract fun onStreetParkingDao(): `[`OnStreetParkingDao`](../../com.skedgo.tripkit.data.database.locations.onstreetparking/-on-street-parking-dao/index.md) |
| [parentStopDao](parent-stop-dao.md) | `abstract fun parentStopDao(): `[`ParentStopDao`](../../skedgo.tripgo.data.timetables/-parent-stop-dao/index.md) |
| [scheduledServiceRealtimeInfoDao](scheduled-service-realtime-info-dao.md) | `abstract fun scheduledServiceRealtimeInfoDao(): `[`ScheduledServiceRealtimeInfoDao`](../../com.skedgo.tripkit.data.database.timetables/-scheduled-service-realtime-info-dao/index.md) |
| [serviceAlertsDao](service-alerts-dao.md) | `abstract fun serviceAlertsDao(): `[`ServiceAlertsDao`](../../com.skedgo.tripkit.data.database.timetables/-service-alerts-dao/index.md) |
| [stopLocationDao](stop-location-dao.md) | `abstract fun stopLocationDao(): `[`StopLocationDao`](../../com.skedgo.tripkit.data.database.stops/-stop-location-dao/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [getInstance](get-instance.md) | `fun getInstance(context: Context): `[`TripKitDatabase`](./index.md) |
