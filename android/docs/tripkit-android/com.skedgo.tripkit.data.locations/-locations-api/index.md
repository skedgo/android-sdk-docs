[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.locations](../index.md) / [LocationsApi](./index.md)

# LocationsApi

`interface LocationsApi`

### Functions

| Name | Summary |
|---|---|
| [fetchLocationsAsync](fetch-locations-async.md) | `abstract fun fetchLocationsAsync(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, body: `[`LocationsRequestBody`](../-locations-request-body/index.md)`!): Observable<`[`LocationsResponse`](../-locations-response/index.md)`!>` |
| [fetchLocationsAsync](fetch-locations-async-get.md) | `abstract fun fetchLocationsAsync(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/)`, lng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/)`, limit: `[`int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/)`, radius: `[`int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/)`, modes: List<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): Observable<`[`LocationsResponse`](../-locations-response/index.md)`>` |
