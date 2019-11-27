[tripkit-android](../../index.md) / [com.skedgo.tripkit.tsp](../index.md) / [RegionInfoApi](./index.md)

# RegionInfoApi

`interface RegionInfoApi`

Retrieves detailed information about covered transport service providers for the specified regions.

 See http://skedgo.github.io/tripgo-api/swagger/#!/Configuration/post_regionInfo_json. See ``[`RegionInfoService`](../-region-info-service/index.md) for easier usage.

### Functions

| Name | Summary |
|---|---|
| [fetchRegionInfo](fetch-region-info.md) | `abstract fun fetchRegionInfo(body: `[`RegionInfoBody`](../-region-info-body/index.md)`!): `[`RegionInfoResponse`](../-region-info-response/index.md)`!` |
| [fetchRegionInfoAsync](fetch-region-info-async.md) | `abstract fun fetchRegionInfoAsync(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, body: `[`RegionInfoBody`](../-region-info-body/index.md)`!): Observable<`[`RegionInfoResponse`](../-region-info-response/index.md)`!>!` |
