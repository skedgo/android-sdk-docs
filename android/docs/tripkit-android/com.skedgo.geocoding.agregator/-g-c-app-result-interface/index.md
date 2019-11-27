[tripkit-android](../../index.md) / [com.skedgo.geocoding.agregator](../index.md) / [GCAppResultInterface](./index.md)

# GCAppResultInterface

`interface GCAppResultInterface : `[`GCResultInterface`](../-g-c-result-interface/index.md)

Information that the user saves in the app

### Types

| Name | Summary |
|---|---|
| [Source](-source/index.md) | `class Source` |

### Functions

| Name | Summary |
|---|---|
| [getAppResultSource](get-app-result-source.md) | `abstract fun getAppResultSource(): Source!` |
| [getSubtitle](get-subtitle.md) | `abstract fun getSubtitle(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [isFavourite](is-favourite.md) | `abstract fun isFavourite(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [AppResultLocationAdapter](../../com.skedgo.tripkit.ui.geocoding/-app-result-location-adapter/index.md) | `class AppResultLocationAdapter : `[`ResultLocationAdapter`](../../com.skedgo.tripkit.ui.geocoding/-result-location-adapter/index.md)`<TripGoPOI!>, `[`GCAppResultInterface`](./index.md) |
| [GCAppResult](../../com.skedgo.geocoding/-g-c-app-result/index.md) | Represents the the minimum information we need to calculate the score for a result obtained from the information stored in the app by the user.`open class GCAppResult : `[`GCResult`](../../com.skedgo.geocoding/-g-c-result/index.md)`, `[`GCAppResultInterface`](./index.md) |
