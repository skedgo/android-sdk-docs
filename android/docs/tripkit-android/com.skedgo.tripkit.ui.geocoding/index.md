[tripkit-android](../index.md) / [com.skedgo.tripkit.ui.geocoding](./index.md)

## Package com.skedgo.tripkit.ui.geocoding

### Types

| Name | Summary |
|---|---|
| [AppResultLocationAdapter](-app-result-location-adapter/index.md) | `class AppResultLocationAdapter : `[`ResultLocationAdapter`](-result-location-adapter/index.md)`<TripGoPOI!>, `[`GCAppResultInterface`](../com.skedgo.geocoding.agregator/-g-c-app-result-interface/index.md) |
| [AutoCompleteResult](-auto-complete-result.md) | `sealed class AutoCompleteResult` |
| [AutoCompleteTask](-auto-complete-task/index.md) | `open class AutoCompleteTask : `[`FetchSuggestions`](../com.skedgo.tripkit.ui.search/-fetch-suggestions/index.md) |
| [CitySelectedEvent](-city-selected-event/index.md) | `interface CitySelectedEvent` |
| [FetchFoursquareLocationsImpl](-fetch-foursquare-locations-impl/index.md) | `class FetchFoursquareLocationsImpl : `[`FetchFoursquareLocations`](../com.skedgo.tripkit.ui.search/-fetch-foursquare-locations/index.md) |
| [FetchGoogleLocationsImpl](-fetch-google-locations-impl/index.md) | `class FetchGoogleLocationsImpl : `[`FetchGoogleLocations`](../com.skedgo.tripkit.ui.search/-fetch-google-locations/index.md) |
| [FetchLocalLocationsImpl](-fetch-local-locations-impl/index.md) | `class FetchLocalLocationsImpl : `[`FetchLocalLocations`](../com.skedgo.tripkit.ui.search/-fetch-local-locations/index.md) |
| [FetchTripGoLocationsImpl](-fetch-trip-go-locations-impl/index.md) | `class FetchTripGoLocationsImpl : `[`FetchTripGoLocations`](../com.skedgo.tripkit.ui.search/-fetch-trip-go-locations/index.md) |
| [FilterSupportedLocations](-filter-supported-locations/index.md) | `interface FilterSupportedLocations` |
| [FilterSupportedLocationsImpl](-filter-supported-locations-impl/index.md) | `class FilterSupportedLocationsImpl : `[`FilterSupportedLocations`](-filter-supported-locations/index.md) |
| [FoursquareGeocoder](-foursquare-geocoder/index.md) | `open class FoursquareGeocoder` |
| [FoursquareResultLocationAdapter](-foursquare-result-location-adapter/index.md) | `class FoursquareResultLocationAdapter : `[`GCFoursquareResultInterface`](../com.skedgo.geocoding.agregator/-g-c-foursquare-result-interface/index.md)`, `[`ResultLocationAdapter`](-result-location-adapter/index.md)`<TripGoPOI!>` |
| [Geocoder](-geocoder/index.md) | `open class Geocoder` |
| [GeocodeResponse](-geocode-response/index.md) | `open class GeocodeResponse` |
| [GeocodeResultAdapter](-geocode-result-adapter/index.md) | `open class GeocodeResultAdapter : JsonDeserializer<`[`Location`](../com.skedgo.android.common.model/-location/index.md)`!>` |
| [GeocoderLive](-geocoder-live/index.md) | `open class GeocoderLive : `[`RegionalGeocoder`](-regional-geocoder/index.md) |
| [GoogleGeocoderLive](-google-geocoder-live/index.md) | `class GoogleGeocoderLive` |
| [GoogleResultLocationAdapter](-google-result-location-adapter/index.md) | `class GoogleResultLocationAdapter : `[`GCGoogleResultInterface`](../com.skedgo.geocoding.agregator/-g-c-google-result-interface/index.md)`, `[`ResultLocationAdapter`](-result-location-adapter/index.md)`<WithoutLocation!>` |
| [HasResults](-has-results/index.md) | `data class HasResults : `[`AutoCompleteResult`](-auto-complete-result.md) |
| [NoConnection](-no-connection.md) | `object NoConnection : `[`AutoCompleteResult`](-auto-complete-result.md) |
| [NoResult](-no-result/index.md) | `data class NoResult : `[`AutoCompleteResult`](-auto-complete-result.md) |
| [RegionalGeocoder](-regional-geocoder/index.md) | `open class RegionalGeocoder : `[`Geocoder`](-geocoder/index.md) |
| [ResultAggregator](-result-aggregator/index.md) | `interface ResultAggregator` |
| [ResultAggregatorImpl](-result-aggregator-impl/index.md) | `class ResultAggregatorImpl : `[`ResultAggregator`](-result-aggregator/index.md) |
| [ResultLocationAdapter](-result-location-adapter/index.md) | `interface ResultLocationAdapter<T : Place!>` |
| [ReviewSummary](-review-summary/index.md) | `open class ReviewSummary` |
| [SkedgoResultLocationAdapter](-skedgo-result-location-adapter/index.md) | `class SkedgoResultLocationAdapter : `[`GCSkedGoResultInterface`](../com.skedgo.geocoding.agregator/-g-c-sked-go-result-interface/index.md)`, `[`ResultLocationAdapter`](-result-location-adapter/index.md)`<TripGoPOI!>` |

### Exceptions

| Name | Summary |
|---|---|
| [UnableToFindPlaceCoordinatesError](-unable-to-find-place-coordinates-error/index.md) | `class UnableToFindPlaceCoordinatesError : `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html) |
