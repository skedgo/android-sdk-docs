[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresult](../index.md) / [TripResultPagerViewModel](./index.md)

# TripResultPagerViewModel

`class TripResultPagerViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Properties

| Name | Summary |
|---|---|
| [currentPage](current-page.md) | `val currentPage: ObservableInt` |
| [fetchingRealtimeStatus](fetching-realtime-status.md) | `val fetchingRealtimeStatus: ObservableBoolean` |
| [selectedTripGroup](selected-trip-group.md) | `val selectedTripGroup: Observable<`[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`>` |
| [tripGroupsBinding](trip-groups-binding.md) | `val tripGroupsBinding: ObservableField<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`>>` |
| [tripSource](trip-source.md) | `val tripSource: BehaviorRelay<TripSource!>` |

### Functions

| Name | Summary |
|---|---|
| [getSortedTripGroups](get-sorted-trip-groups.md) | `fun getSortedTripGroups(args: PagerFragmentArguments): Observable<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [loadFetchingRealtimeStatus](load-fetching-realtime-status.md) | `fun loadFetchingRealtimeStatus(): Observable<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>` |
| [observeInitialPage](observe-initial-page.md) | `fun observeInitialPage(): Observable<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [observeTripGroups](observe-trip-groups.md) | `fun observeTripGroups(): Observable<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [onCreate](on-create.md) | `fun onCreate(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onSavedInstanceState](on-saved-instance-state.md) | `fun onSavedInstanceState(outState: Bundle): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStart](on-start.md) | `fun onStart(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStop](on-stop.md) | `fun onStop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setInitialSelectedTripGroupId](set-initial-selected-trip-group-id.md) | `fun setInitialSelectedTripGroupId(tripGroupId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [trackViewingTrip](track-viewing-trip.md) | `fun trackViewingTrip(): Observable<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [updateSelectedTripGroup](update-selected-trip-group.md) | `fun updateSelectedTripGroup(): Observable<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
