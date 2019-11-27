[tripkit-android](../../index.md) / [com.skedgo.geocoding](../index.md) / [GCResult](./index.md)

# GCResult

`open class GCResult : `[`GCResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-result-interface/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GCResult(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`!, lng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`!)`<br>`GCResult()` |

### Functions

| Name | Summary |
|---|---|
| [getLat](get-lat.md) | `open fun getLat(): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`!` |
| [getLng](get-lng.md) | `open fun getLng(): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`!` |
| [getName](get-name.md) | `open fun getName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [setLat](set-lat.md) | `open fun setLat(lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setLng](set-lng.md) | `open fun setLng(lng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setName](set-name.md) | `open fun setName(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [GCAppResult](../-g-c-app-result/index.md) | Represents the the minimum information we need to calculate the score for a result obtained from the information stored in the app by the user.`open class GCAppResult : `[`GCResult`](./index.md)`, `[`GCAppResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-app-result-interface/index.md) |
| [GCFoursquareResult](../-g-c-foursquare-result/index.md) | Represents the minimum information we need to calculate the score for a foursquare result.`open class GCFoursquareResult : `[`GCResult`](./index.md)`, `[`GCFoursquareResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-foursquare-result-interface/index.md) |
| [GCGoogleResult](../-g-c-google-result/index.md) | `open class GCGoogleResult : `[`GCResult`](./index.md)`, `[`GCGoogleResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-google-result-interface/index.md) |
| [GCSkedgoResult](../-g-c-skedgo-result/index.md) | `open class GCSkedgoResult : `[`GCResult`](./index.md)`, `[`GCSkedGoResultInterface`](../../com.skedgo.geocoding.agregator/-g-c-sked-go-result-interface/index.md) |
