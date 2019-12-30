[tripkit-android](../../index.md) / [com.skedgo.tripkit.tsp](../index.md) / [RegionInfoApi](index.md) / [fetchRegionInfoAsync](./fetch-region-info-async.md)

# fetchRegionInfoAsync

`@POST abstract fun fetchRegionInfoAsync(@Url url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, @Body body: `[`RegionInfoBody`](../-region-info-body/index.md)`!): Observable<`[`RegionInfoResponse`](../-region-info-response/index.md)`!>!`

### Parameters

`url` - [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!: The url is a composition of an URL from ``[`Region#getURLs()`](../../com.skedgo.tripkit.common.model/-region/get-u-r-ls.md) and 'regionInfo.json'.