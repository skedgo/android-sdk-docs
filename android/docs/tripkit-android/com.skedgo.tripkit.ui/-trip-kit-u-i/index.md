[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui](../index.md) / [TripKitUI](./index.md)

# TripKitUI

`@Singleton @Component([AutoCompleteTaskModule, SchedulerFactoryModule, GooglePlacesModule, ConnectivityServiceModule, FetchSuggestionsModule, TripKitUIModule, ContextModule, ErrorLoggerModule, PicassoModule, TripKitModule, DbHelperModule, ServiceViewModelModule, RealTimeRepositoryModule, GetExcludedTransitModesModule, IsTransitModeIncludedRepositoryModule, IsModeIncludedInTripsRepositoryModule, IsModeMinimizedRepositoryModule, ServiceAlertDataModule, ServiceDetailsModule, ServiceDetailItemViewModelModule, TripGroupRepositoryModule, DeparturesModule, EventTrackerModule, LocationStuffModule, MyPersonalDataModule, PreferredTransferTimeRepositoryModule, CyclingSpeedRepositoryModule, WalkingSpeedRepositoryModule, PrioritiesRepositoryModule, GetRoutingConfigModule]) abstract class TripKitUI`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripKitUI()` |

### Properties

| Name | Summary |
|---|---|
| [AUTHORITY](-a-u-t-h-o-r-i-t-y.md) | `static var AUTHORITY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |

### Functions

| Name | Summary |
|---|---|
| [appContext](app-context.md) | `abstract fun appContext(): Context!` |
| [bus](bus.md) | `abstract fun bus(): Bus!` |
| [dbHelper](db-helper.md) | `abstract fun dbHelper(): `[`DbHelper`](../../com.skedgo.tripkit.data.database/-db-helper/index.md)`!` |
| [errorLogger](error-logger.md) | `abstract fun errorLogger(): `[`ErrorLogger`](../../skedgo.tripkit.logging/-error-logger/index.md)`!` |
| [fetchSuggestions](fetch-suggestions.md) | `abstract fun fetchSuggestions(): `[`FetchSuggestions`](../../com.skedgo.tripkit.ui.search/-fetch-suggestions/index.md)`!` |
| [getInstance](get-instance.md) | `open static fun getInstance(): `[`TripKitUI`](./index.md)`!` |
| [homeMapFragmentComponent](home-map-fragment-component.md) | `abstract fun homeMapFragmentComponent(module: HomeMapFragmentModule!): HomeMapFragmentComponent!` |
| [httpClient](http-client.md) | `abstract fun httpClient(): OkHttpClient!` |
| [initialize](initialize.md) | `open static fun initialize(context: Context!, key: `[`Key`](../../skedgo.tripkit.configuration/-key/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [inject](inject.md) | `abstract fun inject(fragment: `[`LocationSearchFragment`](../../com.skedgo.tripkit.ui.search/-location-search-fragment/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`abstract fun inject(fragment: `[`TimetableFragment`](../../com.skedgo.tripkit.ui.timetables/-timetable-fragment/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`abstract fun inject(provider: `[`ServiceStopsProvider`](../../com.skedgo.tripkit.ui.provider/-service-stops-provider/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`abstract fun inject(fragment: `[`ServiceDetailFragment`](../../com.skedgo.tripkit.ui.servicedetail/-service-detail-fragment/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`abstract fun inject(provider: `[`ScheduledStopsProvider`](../../com.skedgo.tripkit.ui.provider/-scheduled-stops-provider/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [picasso](picasso.md) | `abstract fun picasso(): Picasso!` |
| [regionService](region-service.md) | `abstract fun regionService(): `[`RegionService`](../../com.skedgo.tripkit.data.regions/-region-service/index.md)`!` |
| [routeInputViewComponent](route-input-view-component.md) | `abstract fun routeInputViewComponent(): RouteInputViewComponent!` |
| [routesComponent](routes-component.md) | `abstract fun routesComponent(): RoutesComponent!` |
| [routeStore](route-store.md) | `abstract fun routeStore(): RouteStore!` |
| [searchRepository](search-repository.md) | `abstract fun searchRepository(): PlaceSearchRepository!` |
| [serviceStopMapComponent](service-stop-map-component.md) | `abstract fun serviceStopMapComponent(): ServiceStopMapComponent!` |
| [timePickerComponent](time-picker-component.md) | `abstract fun timePickerComponent(): TimePickerComponent!` |
| [timetableComponent](timetable-component.md) | `abstract fun timetableComponent(module: TimetableModule!): TimetableComponent!` |
| [tripDetailsComponent](trip-details-component.md) | `abstract fun tripDetailsComponent(): TripDetailsComponent!` |
| [tripGroupRepository](trip-group-repository.md) | `abstract fun tripGroupRepository(): TripGroupRepository!` |
| [tripSegmentViewModelComponent](trip-segment-view-model-component.md) | `abstract fun tripSegmentViewModelComponent(): TripSegmentViewModelComponent!` |
