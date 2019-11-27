[tripkit-android](../../index.md) / [com.skedgo.geocoding.agregator](../index.md) / [GCFoursquareResultInterface](./index.md)

# GCFoursquareResultInterface

`interface GCFoursquareResultInterface : `[`GCResultInterface`](../-g-c-result-interface/index.md)

### Functions

| Name | Summary |
|---|---|
| [getCategories](get-categories.md) | `abstract fun getCategories(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!` |
| [isVerified](is-verified.md) | `abstract fun isVerified(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [FoursquareResultLocationAdapter](../../com.skedgo.tripkit.ui.geocoding/-foursquare-result-location-adapter/index.md) | `class FoursquareResultLocationAdapter : `[`GCFoursquareResultInterface`](./index.md)`, `[`ResultLocationAdapter`](../../com.skedgo.tripkit.ui.geocoding/-result-location-adapter/index.md)`<TripGoPOI!>` |
| [GCFoursquareResult](../../com.skedgo.geocoding/-g-c-foursquare-result/index.md) | Represents the minimum information we need to calculate the score for a foursquare result.`open class GCFoursquareResult : `[`GCResult`](../../com.skedgo.geocoding/-g-c-result/index.md)`, `[`GCFoursquareResultInterface`](./index.md) |
