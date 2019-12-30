[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresult](../index.md) / [TripSegmentsViewModel](./index.md)

# TripSegmentsViewModel

`class TripSegmentsViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Properties

| Name | Summary |
|---|---|
| [arriveAtTitle](arrive-at-title.md) | `var arriveAtTitle: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [durationTitle](duration-title.md) | `var durationTitle: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [itemBinding](item-binding.md) | `val itemBinding: ItemBinding<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`!>` |
| [itemViewModels](item-view-models.md) | `val itemViewModels: ObservableField<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`!>!>` |
| [segmentViewModels](segment-view-models.md) | `val segmentViewModels: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripSegmentItemViewModel`](../-trip-segment-item-view-model/index.md)`>` |
| [timeZoneId](time-zone-id.md) | `val timeZoneId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [tripGroup](trip-group.md) | `var tripGroup: `[`TripGroup`](../../com.skedgo.tripkit.routing/-trip-group/index.md) |
| [tripGroupObservable](trip-group-observable.md) | `val tripGroupObservable: Observable<`[`TripGroup`](../../com.skedgo.tripkit.routing/-trip-group/index.md)`>` |

### Functions

| Name | Summary |
|---|---|
| [findSegmentPosition](find-segment-position.md) | `fun findSegmentPosition(tripSegment: `[`TripSegment`](../../com.skedgo.tripkit.routing/-trip-segment/index.md)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [loadTripGroup](load-trip-group.md) | `fun loadTripGroup(tripGroupId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCleared](on-cleared.md) | This method will be called when this ViewModel is no longer used and will be destroyed.`fun onCleared(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStart](on-start.md) | `fun onStart(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStop](on-stop.md) | `fun onStop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setInternalBus](set-internal-bus.md) | `fun setInternalBus(bus: Bus): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
