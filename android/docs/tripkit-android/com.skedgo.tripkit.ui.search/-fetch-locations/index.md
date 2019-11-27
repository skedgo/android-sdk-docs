[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.search](../index.md) / [FetchLocations](./index.md)

# FetchLocations

`interface FetchLocations`

### Functions

| Name | Summary |
|---|---|
| [getLocations](get-locations.md) | `abstract fun getLocations(parameters: `[`FetchLocationsParameters`](../-fetch-locations-parameters/index.md)`): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`GCResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-result-interface/index.md)`>>` |

### Inheritors

| Name | Summary |
|---|---|
| [FetchFoursquareLocations](../-fetch-foursquare-locations/index.md) | `interface FetchFoursquareLocations : `[`FetchLocations`](./index.md) |
| [FetchGoogleLocations](../-fetch-google-locations/index.md) | `interface FetchGoogleLocations : `[`FetchLocations`](./index.md) |
| [FetchLocalLocations](../-fetch-local-locations/index.md) | `interface FetchLocalLocations : `[`FetchLocations`](./index.md) |
| [FetchTripGoLocations](../-fetch-trip-go-locations/index.md) | `interface FetchTripGoLocations : `[`FetchLocations`](./index.md) |
