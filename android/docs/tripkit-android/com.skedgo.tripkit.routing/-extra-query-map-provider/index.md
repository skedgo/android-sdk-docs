[tripkit-android](../../index.md) / [com.skedgo.tripkit.routing](../index.md) / [ExtraQueryMapProvider](./index.md)

# ExtraQueryMapProvider

`interface ExtraQueryMapProvider`

A decorator that puts additional query params into the query map that is supplied into ``[`A2bRoutingApi`](../../com.skedgo.tripkit.a2brouting/-a2b-routing-api/index.md). Note that you should only use this when you really do know what you intend to do.

### Functions

| Name | Summary |
|---|---|
| [call](call.md) | Be careful that some entries of this map may override some default entries of the query map of ``[`A2bRoutingApi`](../../com.skedgo.tripkit.a2brouting/-a2b-routing-api/index.md).`abstract fun call(): `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`!>` |
