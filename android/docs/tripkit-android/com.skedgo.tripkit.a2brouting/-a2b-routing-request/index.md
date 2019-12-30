[tripkit-android](../../index.md) / [com.skedgo.tripkit.a2brouting](../index.md) / [A2bRoutingRequest](./index.md)

# A2bRoutingRequest

`@Immutable abstract class A2bRoutingRequest`

### Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | `interface Builder` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `A2bRoutingRequest()` |

### Properties

| Name | Summary |
|---|---|
| [destination](destination.md) | `abstract val destination: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`>` |
| [destinationAddress](destination-address.md) | `abstract val destinationAddress: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [origin](origin.md) | `abstract val origin: `[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`>` |
| [originAddress](origin-address.md) | `abstract val originAddress: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [time](time.md) | `abstract val time: `[`RequestTime`](../-request-time/index.md) |

### Companion Object Functions

| Name | Summary |
|---|---|
| [builder](builder.md) | `fun builder(): Builder` |
