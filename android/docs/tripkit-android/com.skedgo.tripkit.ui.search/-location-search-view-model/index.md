[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.search](../index.md) / [LocationSearchViewModel](./index.md)

# LocationSearchViewModel

`class LocationSearchViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LocationSearchViewModel(context: Context, regionService: `[`RegionService`](../../com.skedgo.tripkit.data.regions/-region-service/index.md)`, bus: Bus, placeSearchRepository: PlaceSearchRepository, fetchSuggestions: `[`FetchSuggestions`](../-fetch-suggestions/index.md)`, errorLogger: `[`ErrorLogger`](../../com.skedgo.tripkit.logging/-error-logger/index.md)`, picasso: Picasso, schedulerFactory: `[`SchedulerFactory`](../../com.skedgo.tripkit.ui.core/-scheduler-factory/index.md)`, errorViewModel: `[`LocationSearchErrorViewModel`](../-location-search-error-view-model/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [allSuggestions](all-suggestions.md) | `val allSuggestions: MergeObservableList<`[`SuggestionViewModel`](../-suggestion-view-model/index.md)`>` |
| [chosenCityName](chosen-city-name.md) | `val chosenCityName: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [currentLocationChosen](current-location-chosen.md) | `val currentLocationChosen: PublishRelay<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [dismiss](dismiss.md) | `val dismiss: PublishRelay<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [errorViewModel](error-view-model.md) | `val errorViewModel: `[`LocationSearchErrorViewModel`](../-location-search-error-view-model/index.md) |
| [fixedSuggestions](fixed-suggestions.md) | `val fixedSuggestions: ObservableList<`[`SuggestionViewModel`](../-suggestion-view-model/index.md)`>` |
| [googleSuggestions](google-suggestions.md) | `val googleSuggestions: ObservableList<`[`GoogleSuggestionViewModel`](../-google-suggestion-view-model/index.md)`>` |
| [itemBinding](item-binding.md) | `val itemBinding: ItemBinding<`[`SuggestionViewModel`](../-suggestion-view-model/index.md)`!>` |
| [locationChosen](location-chosen.md) | `val locationChosen: PublishRelay<`[`Location`](../../com.skedgo.tripkit.common.model/-location/index.md)`>` |
| [pinDropChosen](pin-drop-chosen.md) | `val pinDropChosen: PublishRelay<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [queries](queries.md) | `val queries: PublishRelay<`[`FetchLocationsParameters`](../-fetch-locations-parameters/index.md)`>` |
| [showError](show-error.md) | `val showError: ObservableBoolean` |
| [showGoogleAttribution](show-google-attribution.md) | `val showGoogleAttribution: ObservableBoolean` |
| [showList](show-list.md) | `val showList: ObservableBoolean` |
| [showMiddleProgressBar](show-middle-progress-bar.md) | `val showMiddleProgressBar: ObservableBoolean` |
| [showRefreshing](show-refreshing.md) | `val showRefreshing: ObservableBoolean` |
| [unableToFindPlaceCoordinatesError](unable-to-find-place-coordinates-error.md) | `val unableToFindPlaceCoordinatesError: Observable<`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [bounds](bounds.md) | `fun bounds(): LatLngBounds` |
| [center](center.md) | `fun center(): LatLng` |
| [changeCity](change-city.md) | `fun changeCity(data: Intent): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [goBack](go-back.md) | `fun goBack(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [handleArgs](handle-args.md) | `fun handleArgs(args: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [loadCity](load-city.md) | `fun loadCity(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [observeGoogleAttribution](observe-google-attribution.md) | `fun observeGoogleAttribution(suggestions: Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<Place>>): Observable<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [onQueryTextChanged](on-query-text-changed.md) | `fun onQueryTextChanged(query: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onSuggestionItemClick](on-suggestion-item-click.md) | `fun onSuggestionItemClick(choice: `[`SearchSuggestionChoice`](../-search-suggestion-choice/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onTextSubmit](on-text-submit.md) | `fun onTextSubmit(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
