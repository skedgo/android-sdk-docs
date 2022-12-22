[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.locations](../index.md) / [LocationsApi](index.md) / [fetchLocationsAsync](./fetch-locations-async.md)

# fetchLocationsAsync

`@GET fun fetchLocationsAsync(@Url url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/)`, lng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/)`, limit: `[`int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/)`, radius: `[`int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/)`, modes: List<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`> ): Observable<`[`LocationsResponse`](../-locations-response/index.md)`!>!`

### Parameters

`url` - [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html): A concatenation of an item of Region#getURLs() and "locations.json". For example, "https://sydney-au-nsw-sydney.tripgo.skedgo.com/satapp/locations.json".

`lat` - [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/): Latitude from [Location](../../com.skedgo.tripkit.common.model/-location/index.md)

`lng` - [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/): Longitude from [Location](../../com.skedgo.tripkit.common.model/-location/index.md)

`limit` - [int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/)

`radius` - [int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/)

`modes` - List<[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)>
