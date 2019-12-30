[tripkit-android](../../index.md) / [com.skedgo.tripkit.a2brouting](../index.md) / [FailoverA2bRoutingApi](./index.md)

# FailoverA2bRoutingApi

`open class FailoverA2bRoutingApi`

A wrapper of ``[`A2bRoutingApi`](../-a2b-routing-api/index.md) that requests `routing.json` on multiple servers w/ failover.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FailoverA2bRoutingApi(resources: Resources!, gson: Gson!, a2bRoutingApi: `[`A2bRoutingApi`](../-a2b-routing-api/index.md)`!)` |

### Functions

| Name | Summary |
|---|---|
| [fetchRoutesAsync](fetch-routes-async.md) | Fetches routes on multiple base urls serially. If it fails on one url, it'll failover on next url.`open fun fetchRoutesAsync(baseUrls: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!, modes: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!, excludedTransitModes: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!, excludeStops: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!, options: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`!>!): Observable<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripGroup`](../../com.skedgo.tripkit.routing/-trip-group/index.md)`!>!>!` |
