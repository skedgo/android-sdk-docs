[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.locations](../index.md) / [LocationsApi](index.md) / [fetchLocationsAsync](./fetch-locations-async.md)

# fetchLocationsAsync

`@POST abstract fun fetchLocationsAsync(@Url url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, @Body body: `[`LocationsRequestBody`](../-locations-request-body/index.md)`!): Observable<`[`LocationsResponse`](../-locations-response/index.md)`!>!`

### Parameters

`url` - [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!: A concatenation of an item of Region#getURLs() and "locations.json". For example, "https://sydney-au-nsw-sydney.tripgo.skedgo.com/satapp/locations.json".