[tripkit-android](../../index.md) / [com.skedgo](../index.md) / [TripKit](./index.md)

# TripKit

`@Singleton @Component([HttpClientModule, A2bRoutingDataModule, TspModule, MainModule]) abstract class TripKit`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripKit()` |

### Functions

| Name | Summary |
|---|---|
| [a2bRoutingComponent](a2b-routing-component.md) | `abstract fun a2bRoutingComponent(): `[`A2bRoutingComponent`](../../com.skedgo.tripkit.android/-a2b-routing-component.md)`!` |
| [analyticsComponent](analytics-component.md) | `abstract fun analyticsComponent(): `[`AnalyticsComponent`](../../com.skedgo.tripkit.android/-analytics-component/index.md)`!` |
| [configs](configs.md) | `abstract fun configs(): `[`Configs`](../../com.skedgo.tripkit/-configs/index.md)`!` |
| [dateTimeComponent](date-time-component.md) | `abstract fun dateTimeComponent(): `[`DateTimeComponent`](../../com.skedgo.tripkit.android/-date-time-component/index.md)`!` |
| [getBookingResolver](get-booking-resolver.md) | `abstract fun getBookingResolver(): `[`BookingResolver`](../../com.skedgo.tripkit.bookingproviders/-booking-resolver/index.md)`!` |
| [getErrorHandler](get-error-handler.md) | `abstract fun getErrorHandler(): Consumer<`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`!>!` |
| [getInstance](get-instance.md) | `open static fun getInstance(): `[`TripKit`](./index.md)`!` |
| [getLocationInfoService](get-location-info-service.md) | `abstract fun getLocationInfoService(): `[`LocationInfoService`](../../com.skedgo.tripkit/-location-info-service/index.md)`!` |
| [getOkHttpClient3](get-ok-http-client3.md) | `abstract fun getOkHttpClient3(): OkHttpClient!` |
| [getRegionService](get-region-service.md) | `abstract fun getRegionService(): `[`RegionService`](../../com.skedgo.tripkit.data.regions/-region-service/index.md)`!` |
| [getRouteService](get-route-service.md) | `abstract fun getRouteService(): `[`RouteService`](../../com.skedgo.tripkit.a2brouting/-route-service/index.md)`!` |
| [getTripUpdater](get-trip-updater.md) | `abstract fun getTripUpdater(): `[`TripUpdater`](../../com.skedgo.tripkit/-trip-updater/index.md)`!` |
| [initialize](initialize.md) | This gives a chance to provide a custom ``[`TripKit`](./index.md). One idea is that we can create ``[`DaggerTripKit`](#) w/ some customized modules. `open static fun initialize(context: Context, tripKit: `[`TripKit`](./index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`open static fun initialize(configs: `[`Configs`](../../com.skedgo.tripkit/-configs/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [isInitialized](is-initialized.md) | `open static fun isInitialized(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
