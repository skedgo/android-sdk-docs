[tripkit-android](../index.md) / [com.skedgo.tripkit.ui.tripresult](./index.md)

## Package com.skedgo.tripkit.ui.tripresult

### Types

| Name | Summary |
|---|---|
| [GetAlternativeTripForAlternativeService](-get-alternative-trip-for-alternative-service/index.md) | `open class GetAlternativeTripForAlternativeService` |
| [IsLocationPermissionGranted](-is-location-permission-granted/index.md) | `open class IsLocationPermissionGranted` |
| [MapCameraUpdate](-map-camera-update/index.md) | A view model for [GoogleMap](#) to know when it should [GoogleMap.moveCamera](#) or [GoogleMap.animateCamera](#)`sealed class MapCameraUpdate` |
| [TripGroupsPagerAdapter](-trip-groups-pager-adapter/index.md) | `open class TripGroupsPagerAdapter : FragmentStatePagerAdapter` |
| [TripResultMapFragment](-trip-result-map-fragment/index.md) | `open class TripResultMapFragment : `[`LocationEnhancedMapFragment`](../com.skedgo.tripkit.ui.map/-location-enhanced-map-fragment/index.md) |
| [TripResultPagerFragment](-trip-result-pager-fragment/index.md) | `open class TripResultPagerFragment : `[`RxFragment`](../com.skedgo.tripkit.ui.core.rxlifecyclecomponents/-rx-fragment/index.md)`, OnPageChangeListener, OnTripKitButtonClickListener` |
| [TripResultPagerViewModel](-trip-result-pager-view-model/index.md) | `class TripResultPagerViewModel : `[`RxViewModel`](../com.skedgo.tripkit.ui.core/-rx-view-model/index.md) |
| [TripSegmentItemViewModel](-trip-segment-item-view-model/index.md) | `class TripSegmentItemViewModel : `[`RxViewModel`](../com.skedgo.tripkit.ui.core/-rx-view-model/index.md) |
| [TripSegmentListFragment](-trip-segment-list-fragment/index.md) | `class TripSegmentListFragment : `[`RxFragment`](../com.skedgo.tripkit.ui.core.rxlifecyclecomponents/-rx-fragment/index.md)`, OnClickListener` |
| [TripSegmentsViewModel](-trip-segments-view-model/index.md) | `class TripSegmentsViewModel : `[`RxViewModel`](../com.skedgo.tripkit.ui.core/-rx-view-model/index.md) |
| [UpdateTripForRealtime](-update-trip-for-realtime/index.md) | `open class UpdateTripForRealtime` |
| [WaypointTask](-waypoint-task/index.md) | https://redmine.buzzhives.com/projects/buzzhives/wiki/Routing_API#Trips-from-waypoint`open class WaypointTask : SingleOnSubscribe<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripGroup`](../skedgo.tripkit.routing/-trip-group/index.md)`!>!>` |
| [WayPointTaskParam](-way-point-task-param/index.md) | `sealed class WayPointTaskParam` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [com.google.android.gms.maps.model.LatLngBounds](com.google.android.gms.maps.model.-lat-lng-bounds/index.md) |  |
| [kotlin.collections.List](kotlin.collections.-list/index.md) |  |

### Properties

| Name | Summary |
|---|---|
| [CameraUpdatePadding](-camera-update-padding.md) | `const val CameraUpdatePadding: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [KEY_TRIP_GROUP_ID](-k-e-y_-t-r-i-p_-g-r-o-u-p_-i-d.md) | `const val KEY_TRIP_GROUP_ID: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [OneKilometers](-one-kilometers.md) | `const val OneKilometers: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [ZoomOnSingleLocation](-zoom-on-single-location.md) | `const val ZoomOnSingleLocation: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [ZoomToCoverFirstOneKilometers](-zoom-to-cover-first-one-kilometers.md) | `const val ZoomToCoverFirstOneKilometers: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
