![TripKitMapFragment](img/TripKitMapFragment.png)

The `TripKitMapFragment` is a map, based ultimately on a `SupportMapFragment`, that automatically integrates with SkedGo's backend, 
display transit information without any additional intervention. Assuming that you've added your TripGo API Token as described
in the [Setup](index.md#setup), you can add the fragment directly to your layout, and icons will automatically be downloaded
and displayed.

````xml tab="Layout"
    <fragment
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:id="@+id/map"
            android:name="com.skedgo.tripkit.ui.map.home.TripKitMapFragment"/>
````

When the user clicks on a stop icon, a small info window is displayed with information about the stop. If you provide
an `OnInfoWindowClickListener`, you'll be notified when the user clicks on that info window.

````kotlin tab="Kotlin"
        mapFragment.setOnInfoWindowClickListener { location ->
            if (location is ScheduledStop) {
                showTimetable(location)
            }
        }
````
