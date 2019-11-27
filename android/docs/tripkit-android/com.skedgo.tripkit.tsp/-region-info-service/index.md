[tripkit-android](../../index.md) / [com.skedgo.tripkit.tsp](../index.md) / [RegionInfoService](./index.md)

# RegionInfoService

`open class RegionInfoService`

A facade of ``[`RegionInfoApi`](../-region-info-api/index.md) that has failover on multiple servers.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RegionInfoService(regionInfoApiLazy: Lazy<`[`RegionInfoApi`](../-region-info-api/index.md)`!>!)` |

### Functions

| Name | Summary |
|---|---|
| [fetchRegionInfoAsync](fetch-region-info-async.md) | `open fun fetchRegionInfoAsync(baseUrls: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!, regionName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): Observable<`[`RegionInfo`](../../com.skedgo.tripkit.data.tsp/-region-info/index.md)`!>!` |
