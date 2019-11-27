[tripkit-android](../../index.md) / [com.skedgo.geocoding.agregator](../index.md) / [GCSkedGoResultInterface](./index.md)

# GCSkedGoResultInterface

`interface GCSkedGoResultInterface : `[`GCResultInterface`](../-g-c-result-interface/index.md)

### Functions

| Name | Summary |
|---|---|
| [getPopularity](get-popularity.md) | `abstract fun getPopularity(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getResultClass](get-result-class.md) | `abstract fun getResultClass(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |

### Inheritors

| Name | Summary |
|---|---|
| [GCSkedgoResult](../../com.skedgo.geocoding/-g-c-skedgo-result/index.md) | `open class GCSkedgoResult : `[`GCResult`](../../com.skedgo.geocoding/-g-c-result/index.md)`, `[`GCSkedGoResultInterface`](./index.md) |
| [SkedgoResultLocationAdapter](../../com.skedgo.tripkit.ui.geocoding/-skedgo-result-location-adapter/index.md) | `class SkedgoResultLocationAdapter : `[`GCSkedGoResultInterface`](./index.md)`, `[`ResultLocationAdapter`](../../com.skedgo.tripkit.ui.geocoding/-result-location-adapter/index.md)`<TripGoPOI!>` |
