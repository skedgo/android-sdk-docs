[tripkit-android](../../index.md) / [com.skedgo.tripkit.a2brouting](../index.md) / [A2bRoutingApi](./index.md)

# A2bRoutingApi

`interface A2bRoutingApi`

Calculates door-to-door trips for the specified mode(s). See more at https://skedgo.github.io/tripgo-api/#tag/Routing%2Fpaths%2F~1routing.json%2Fget.

### Functions

| Name | Summary |
|---|---|
| [execute](execute.md) | `abstract fun execute(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, modes: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!, excludedTransitModes: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!, excludeStops: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!, options: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`!>!): Observable<`[`RoutingResponse`](../../skedgo.tripkit.routing/-routing-response/index.md)`!>!` |
