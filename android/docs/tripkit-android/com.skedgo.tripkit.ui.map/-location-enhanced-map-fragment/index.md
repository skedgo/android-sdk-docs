[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map](../index.md) / [LocationEnhancedMapFragment](./index.md)

# LocationEnhancedMapFragment

`open class LocationEnhancedMapFragment : `[`BaseMapFragment`](../-base-map-fragment/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LocationEnhancedMapFragment()` |

### Functions

| Name | Summary |
|---|---|
| [animateToMyLocation](animate-to-my-location.md) | `open fun animateToMyLocation(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreate](on-create.md) | `open fun onCreate(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateView](on-create-view.md) | `open fun onCreateView(inflater: LayoutInflater, container: ViewGroup?, savedInstanceState: Bundle?): View?` |

### Inheritors

| Name | Summary |
|---|---|
| [ServiceStopMapFragment](../../com.skedgo.tripkit.ui.map.servicestop/-service-stop-map-fragment/index.md) | `open class ServiceStopMapFragment : `[`LocationEnhancedMapFragment`](./index.md)`, OnInfoWindowClickListener, InfoWindowAdapter, OnTimetableEntrySelectedListener, OnScheduledStopClickListener` |
| [TripKitMapFragment](../../com.skedgo.tripkit.ui.map.home/-trip-kit-map-fragment/index.md) | A map component for an app. It automatically integrates with SkedGo's backend, display transit information without any additional intervention. Being a fragment, it can very easily be added to an activity's layout.

```
<fragment
              android:layout_width="match_parent"
              android:layout_height="match_parent"
              android:id="@+id/map"
              android:name="com.skedgo.tripkit.ui.map.home.TripKitMapFragment"/>  <br>```
<br> Your app **must** provide a TripGo API token as `R.string.skedgo_api_key`.`open class TripKitMapFragment : `[`LocationEnhancedMapFragment`](./index.md)`, OnInfoWindowClickListener, OnMapLongClickListener, OnCameraChangeListener, OnMarkerClickListener` |
| [TripResultMapFragment](../../com.skedgo.tripkit.ui.tripresult/-trip-result-map-fragment/index.md) | `open class TripResultMapFragment : `[`LocationEnhancedMapFragment`](./index.md) |
