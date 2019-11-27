[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.core](../index.md) / [RxViewModel](./index.md)

# RxViewModel

`abstract class RxViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RxViewModel()` |

### Properties

| Name | Summary |
|---|---|
| [compositeSubscription](composite-subscription.md) | `val compositeSubscription: CompositeDisposable` |

### Functions

| Name | Summary |
|---|---|
| [autoClear](auto-clear.md) | `fun <T> Observable<T>.autoClear(): Observable<T>`<br>`fun Disposable.autoClear(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCleared](on-cleared.md) | This method will be called when this ViewModel is no longer used and will be destroyed.`open fun onCleared(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [LocationSearchViewModel](../../com.skedgo.tripkit.ui.search/-location-search-view-model/index.md) | `class LocationSearchViewModel : `[`RxViewModel`](./index.md) |
| [MapViewModel](../../com.skedgo.tripkit.ui.map.home/-map-view-model/index.md) | `class MapViewModel : `[`RxViewModel`](./index.md) |
| [RouteInputViewModel](../../com.skedgo.tripkit.ui.routeinput/-route-input-view-model/index.md) | `class RouteInputViewModel : `[`RxViewModel`](./index.md) |
| [ServiceDetailItemViewModel](../../com.skedgo.tripkit.ui.servicedetail/-service-detail-item-view-model/index.md) | `class ServiceDetailItemViewModel : `[`RxViewModel`](./index.md) |
| [ServiceDetailViewModel](../../com.skedgo.tripkit.ui.servicedetail/-service-detail-view-model/index.md) | `class ServiceDetailViewModel : `[`RxViewModel`](./index.md) |
| [ServiceStopMapViewModel](../../com.skedgo.tripkit.ui.map.servicestop/-service-stop-map-view-model/index.md) | `class ServiceStopMapViewModel : `[`RxViewModel`](./index.md) |
| [ServiceViewModel](../../com.skedgo.tripkit.ui.timetables/-service-view-model/index.md) | `abstract class ServiceViewModel : `[`RxViewModel`](./index.md) |
| [TimetableViewModel](../../com.skedgo.tripkit.ui.timetables/-timetable-view-model/index.md) | `class TimetableViewModel : `[`RxViewModel`](./index.md) |
| [TripResultListViewModel](../../com.skedgo.tripkit.ui.tripresults/-trip-result-list-view-model/index.md) | `class TripResultListViewModel : `[`RxViewModel`](./index.md) |
| [TripResultMapViewModel](../../com.skedgo.tripkit.ui.map/-trip-result-map-view-model/index.md) | `class TripResultMapViewModel : `[`RxViewModel`](./index.md) |
| [TripResultPagerViewModel](../../com.skedgo.tripkit.ui.tripresult/-trip-result-pager-view-model/index.md) | `class TripResultPagerViewModel : `[`RxViewModel`](./index.md) |
| [TripResultTransportItemViewModel](../../com.skedgo.tripkit.ui.tripresults/-trip-result-transport-item-view-model/index.md) | `class TripResultTransportItemViewModel : `[`RxViewModel`](./index.md) |
| [TripResultViewModel](../../com.skedgo.tripkit.ui.tripresults/-trip-result-view-model/index.md) | `class TripResultViewModel : `[`RxViewModel`](./index.md) |
| [TripSegmentItemViewModel](../../com.skedgo.tripkit.ui.tripresult/-trip-segment-item-view-model/index.md) | `class TripSegmentItemViewModel : `[`RxViewModel`](./index.md) |
| [TripSegmentsViewModel](../../com.skedgo.tripkit.ui.tripresult/-trip-segments-view-model/index.md) | `class TripSegmentsViewModel : `[`RxViewModel`](./index.md) |
| [TripSegmentViewModel](../../com.skedgo.tripkit.ui.tripresults/-trip-segment-view-model/index.md) | `class TripSegmentViewModel : `[`RxViewModel`](./index.md) |
