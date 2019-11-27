[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.utils](../index.md) / [MainThreadBus](./index.md)

# MainThreadBus

`open class MainThreadBus : Bus`

A custom ``[`Bus`](#) that posts events from any thread and lets subscribers receive them on the main thread.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `MainThreadBus(errorHandler: Consumer<`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`!>!)` |

### Functions

| Name | Summary |
|---|---|
| [post](post.md) | Posts an event and expects to handle it on the main thread.`fun post(event: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
