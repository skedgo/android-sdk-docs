[tripkit-android](../../index.md) / [com.skedgo.geocoding](../index.md) / [GCAppResult](./index.md)

# GCAppResult

`open class GCAppResult : `[`GCResult`](../-g-c-result/index.md)`, `[`GCAppResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-app-result-interface/index.md)

Represents the the minimum information we need to calculate the score for a result obtained from the information stored in the app by the user.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GCAppResult(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, address: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, isFavourite: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, source: Source)` |

### Functions

| Name | Summary |
|---|---|
| [getAppResultSource](get-app-result-source.md) | `open fun getAppResultSource(): Source!` |
| [getSubtitle](get-subtitle.md) | `open fun getSubtitle(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [isFavourite](is-favourite.md) | `open fun isFavourite(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setAppResultSource](set-app-result-source.md) | `open fun setAppResultSource(source: Source!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setIsFavourite](set-is-favourite.md) | `open fun setIsFavourite(favourite: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSubtitle](set-subtitle.md) | `open fun setSubtitle(subtitle: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
