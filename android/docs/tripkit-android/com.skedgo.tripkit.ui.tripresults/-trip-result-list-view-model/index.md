[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresults](../index.md) / [TripResultListViewModel](./index.md)

# TripResultListViewModel

`class TripResultListViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripResultListViewModel(context: Context, tripGroupRepository: TripGroupRepository, routingStatusRepositoryLazy: Lazy<`[`RoutingStatusRepository`](../../skedgo.tripkit.routingstatus/-routing-status-repository/index.md)`>, tripResultViewModelProvider: Provider<`[`TripResultViewModel`](../-trip-result-view-model/index.md)`>, getSortedTripGroupsWithRoutingStatusProvider: Provider<`[`GetSortedTripGroupsWithRoutingStatus`](../../com.skedgo.tripkit.ui.routing/-get-sorted-trip-groups-with-routing-status/index.md)`>, tripResultTransportItemViewModelProvider: Provider<`[`TripResultTransportItemViewModel`](../-trip-result-transport-item-view-model/index.md)`>, regionService: `[`RegionService`](../../com.skedgo.tripkit.data.regions/-region-service/index.md)`, routeService: `[`RouteService`](../../com.skedgo.tripkit.a2brouting/-route-service/index.md)`, transitModeFilter: `[`TransitModeFilter`](../../com.skedgo.tripkit/-transit-mode-filter/index.md)`, errorLogger: `[`ErrorLogger`](../../skedgo.tripkit.logging/-error-logger/index.md)`, getTransportModePreferencesByRegion: `[`GetTransportModePreferencesByRegion`](../-get-transport-mode-preferences-by-region/index.md)`, sorterProvider: Provider<`[`TripGroupsSorter`](../-trip-groups-sorter/index.md)`>, isModeIncludedInTripsRepository: IsModeIncludedInTripsRepository, performRouting: `[`PerformRouting`](../../com.skedgo.tripkit.ui.routing/-perform-routing/index.md)`, routingTimeViewModelMapper: `[`RoutingTimeViewModelMapper`](../../com.skedgo.tripkit.ui.trip.options/-routing-time-view-model-mapper/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [fromName](from-name.md) | `val fromName: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [isLoading](is-loading.md) | `val isLoading: ObservableBoolean` |
| [itemBinding](item-binding.md) | `val itemBinding: ItemBinding<`[`TripResultViewModel`](../-trip-result-view-model/index.md)`!>` |
| [onItemClicked](on-item-clicked.md) | `val onItemClicked: PublishRelay<ViewTrip!>` |
| [query](query.md) | `lateinit var query: `[`Query`](../../com.skedgo.android.common.model/-query/index.md) |
| [results](results.md) | `val results: DiffObservableList<`[`TripResultViewModel`](../-trip-result-view-model/index.md)`>` |
| [showTransport](show-transport.md) | `val showTransport: ObservableBoolean` |
| [timeLabel](time-label.md) | `val timeLabel: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [toName](to-name.md) | `val toName: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [transportBinding](transport-binding.md) | `val transportBinding: ItemBinding<`[`TripResultTransportItemViewModel`](../-trip-result-transport-item-view-model/index.md)`!>` |
| [transportModes](transport-modes.md) | `val transportModes: ObservableField<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TripResultTransportItemViewModel`](../-trip-result-transport-item-view-model/index.md)`>>` |

### Functions

| Name | Summary |
|---|---|
| [changeQuery](change-query.md) | `fun changeQuery(newQuery: `[`Query`](../../com.skedgo.android.common.model/-query/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getTransport](get-transport.md) | `fun getTransport(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [load](load.md) | `fun load(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [loadFromStore](load-from-store.md) | `fun loadFromStore(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [reload](reload.md) | `fun reload(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTimeLabel](set-time-label.md) | `fun setTimeLabel(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setup](setup.md) | `fun setup(_query: `[`Query`](../../com.skedgo.android.common.model/-query/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [transportLayoutClicked](transport-layout-clicked.md) | `fun transportLayoutClicked(view: View): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [updateQueryTime](update-query-time.md) | `fun updateQueryTime(timeTag: `[`TimeTag`](../../com.skedgo.android.common.model/-time-tag/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
