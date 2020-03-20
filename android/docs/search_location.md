Most of the time, you'll be interested in things involving Locations - a starting location, a destination location,
or possibly a service stop location. We provide a few components to help you find them.

## RouteInputView
![RouteInputView](img/RouteInputView.png)

The [`RouteInputView`](tripkit-android/com.skedgo.tripkit.ui.routeinput/-route-input-view/index.md) is a view that can be overlaid on top of a map, such as the  [TripKit Map Fragment](tripkit_map_fragment.md), 
providing a UI for displaying the origin and destination locations, as well as departure/arrival time.

The [`RouteInputView`](tripkit-android/com.skedgo.tripkit.ui.routeinput/-route-input-view/index.md) doesn't provide any logic, it's simply there to display information and pass along click events.
You'll need to keep track of the chosen Locations yourself by adding an [`OnRouteWidgetClickedListener`](tripkit-android/com.skedgo.tripkit.ui.routeinput/-route-input-view/-on-route-widget-clicked-listener/index.md).

```xml tab="Layout"
<FrameLayout android:layout_width="match_parent"
            android:layout_height="match_parent">

    <fragment android:layout_width="match_parent"
              android:layout_height="match_parent"
              android:id="@+id/map"
              android:name="com.skedgo.tripkit.ui.map.home.TripKitMapFragment"/>
    <com.skedgo.tripkit.ui.routeinput.RouteInputView
            android:id="@+id/routeInputView"
            android:layout_height="wrap_content"
            android:layout_gravity="center_horizontal|top"
            android:layout_marginTop="16dp"
            android:layout_marginStart="16dp"
            android:layout_marginEnd="16dp"
            android:layout_width="match_parent"/>
</FrameLayout>
```

```kotlin tab="Kotlin"
    private var fromLocation: Location? = null
    private var toLocation: Location? = null

    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        routeInputView.setOnRouteWidgetClickedListener { widget ->
            when(widget) {
                RouteInputView.OnRouteWidgetClickedListener.Widget.START -> showSearchForStart()
                RouteInputView.OnRouteWidgetClickedListener.Widget.DESTINATION -> showSearchForDestination()
                RouteInputView.OnRouteWidgetClickedListener.Widget.SWAPPED -> startAndDestinationSwapped()
                RouteInputView.OnRouteWidgetClickedListener.Widget.ROUTE ->routeButtonSelected()
                RouteInputView.OnRouteWidgetClickedListener.Widget.TIME -> timeButtonSelected()
            }
    }
```

```java tab="Java"
    private Location fromLocation = null
    private Location toLocation = null

    @Override
    public void onCreate(@Nullable Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        routeInputView.setOnRouteWidgetClickedListener(new RouteInputView.OnRouteWidgetClickedListener() {
            @Override
            public void widgetClicked(@NotNull Widget button) {
                switch(button) {
                    case START:
                        showSearchForStart();
                        break;
                    case DESTINATION:
                        showSearchForDestination();
                        break;
                    case SWAPPED:
                        startAndDestinationSwapped();
                        break;
                    case ROUTE:
                        routeButtonSelected();
                        break;
                    case TIME:
                        timeButtonSelected();
                        break;
                }
            }                   
        });
    }
```

The [`widgetClicked`](tripkit-android/com.skedgo.tripkit.ui.routeinput/-route-input-view/-on-route-widget-clicked-listener/widget-clicked.md) 
function of your  [`OnRouteWidgetClickedListener`](tripkit-android/com.skedgo.tripkit.ui.routeinput/-route-input-view/-on-route-widget-clicked-listener/index.md) will give you an [enum value](tripkit-android/com.skedgo.tripkit.ui.routeinput/-route-input-view/-on-route-widget-clicked-listener/-widget/index.md) of the widget that was 
clicked.

When the user clicks on the start or destination fields, you could launch a [LocationSearchFragment](#locationsearchfragment) to allow them to 
search for a location. When they click on the time button, you can show them a [TripKitDateTimePickerDialogFragment](#tripkitdatetimepickerdialogfragment) 
to set their departure or arrival time, and when they click on the *Route* button, you could load the [TripResultListFragment](trip_results.md).

## TripKitDateTimePickerDialogFragment
![TripKitDateTimePickerDialogFragment](img/TripKitTimeDatePickerDialog.png)

The [`TripKitTimeDatePickerDialogFragment`](tripkit-android/com.skedgo.tripkit.ui.dialog/-trip-kit-date-time-picker-dialog-fragment/index.md) displays a date and time picker so the user can choose their departure or arrival time. 

Use the [`TripKitDateTimePickerDialogFragment.Builder`](tripkit-android/com.skedgo.tripkit.ui.dialog/-trip-kit-date-time-picker-dialog-fragment/-builder/index.md) to build your fragment fluently. If you know the start and 
destination locations, you can pass that using [`withLocations`](tripkit-android/com.skedgo.tripkit.ui.dialog/-trip-kit-date-time-picker-dialog-fragment/-builder/with-locations.md) to automatically handle timezone issues. 

To configure the initial values, you can either use [`withTimeTag`](tripkit-android/com.skedgo.tripkit.ui.dialog/-trip-kit-date-time-picker-dialog-fragment/-builder/with-time-tag.md) to give the fragment a `TimeTag`, or you can use
`withTimeType` and `timeMillis`.

The `OnTimeSelectedListener` will return a [`TimeTag`](tripkit-android/com.skedgo.android.common.model/-time-tag/index.md) after the user has finalized their choice.

````kotlin tab="Kotlin"
var fragment = TripKitDateTimePickerDialogFragment.Builder()
        .withLocations(toLocation, fromLocation)
        .withTimeTag(timeTagForQuery)
        .build()

fragment.setOnTimeSelectedListener { tag ->
    // Show the correct time on the RouteInputView button when they've changed the time
    val timeZone: String? = when (tag.type) {
        TIME_TYPE_LEAVE_AFTER -> { toLocation?.timeZone }
        TIME_TYPE_ARRIVE_BY -> { fromLocation?.timeZone }
        else -> null
    }
    routeInputView.setTimeButton(tag.formatString(this, timeZone))
}
fragment.show(supportFragmentManager, "timePicker")

````
## LocationSearchFragment

The [`LocationSearchFragment`](tripkit-android/com.skedgo.tripkit.ui.search/-location-search-fragment/index.md) is a self-contained location search component which merges search results from both SkedGo's
search results as well as Google Places. 

![LocationSearchFragment.png](img/LocationSearchFragment.png)


````kotlin tab="Kotlin"
        LocationSearchFragment.Builder()
                .withBounds(mMap.projection.visibleRegion.latLngBounds)
                .near(mMap.cameraPosition.target)
                .withHint(getString(R.string.search))
                .allowCurrentLocation(true)
                .allowDropPin()
                .build()
````

You can style the individual results by changing a few values.

**dimens.xml**

| Name                    | Description|
|-------------------------|------------|
| tripkit_search_result_icon_size | Sets the size of the result icon. The default is `24dp`. |
| tripkit_search_result_divider_inset | Sets the inset of the dividing line between items. The default is `0dp`.|

<br/>

**styles.xml**

| Name | Description|
|------|------------|
| tripkit_search_result_title | Sets the style of the result title.|
| tripkit_search_result_subtitle | Sets the style of the result subtitle. |

<br/>

The [`LocationSearchFragment.Builder()`](tripkit-android/com.skedgo.tripkit.ui.search/-location-search-fragment/-builder/index.md) can be configured with a few different settings.

| Function                 | Description |
|--------------------------|-------------|
| withBounds(LatLngBounds) | Used for Google Places searches. In our example, we use the map's visible boundaries. |
| near(LatLng) | Used for TripGo searches. In our example, we focus on the center of the map. |
| withHint(String) | Sets the EditText's hint. |
| initialQuery(String) | Set a query. |
| allowCurrentLocation(Boolean) | When `true`, show a permanent option for "Current Location" at the top of the results list|
| allowDropPin(Boolean) | When `true`, show a permanent option for "Choose on Map" at the top of the results list|

