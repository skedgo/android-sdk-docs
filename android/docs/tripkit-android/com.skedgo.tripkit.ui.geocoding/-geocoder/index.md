[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.geocoding](../index.md) / [Geocoder](./index.md)

# Geocoder

`open class Geocoder`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Geocoder()` |

### Properties

| Name | Summary |
|---|---|
| [GEOCODE_METHOD](-g-e-o-c-o-d-e_-m-e-t-h-o-d.md) | `static val GEOCODE_METHOD: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [mGson](m-gson.md) | `var mGson: Gson!` |
| [mNearLatitude](m-near-latitude.md) | `var mNearLatitude: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [mNearLongitude](m-near-longitude.md) | `var mNearLongitude: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [PARAM_ALLOW_GOOGLE](-p-a-r-a-m_-a-l-l-o-w_-g-o-o-g-l-e.md) | `static val PARAM_ALLOW_GOOGLE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [PARAM_ALLOW_YELP](-p-a-r-a-m_-a-l-l-o-w_-y-e-l-p.md) | `static val PARAM_ALLOW_YELP: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [PARAM_NEAR](-p-a-r-a-m_-n-e-a-r.md) | `static val PARAM_NEAR: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [PARAM_QUERY](-p-a-r-a-m_-q-u-e-r-y.md) | `static val PARAM_QUERY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [asParams](as-params.md) | `open fun asParams(query: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<Pair<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`!>!>!` |
| [getNearLatitude](get-near-latitude.md) | `open fun getNearLatitude(): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getNearLongitude](get-near-longitude.md) | `open fun getNearLongitude(): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getServiceUrl](get-service-url.md) | `open fun getServiceUrl(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [query](query.md) | `open fun query(query: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Location`](../../com.skedgo.tripkit.common.model/-location/index.md)`!>!` |
| [setNearLatitude](set-near-latitude.md) | `open fun setNearLatitude(nearLatitude: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Geocoder`](./index.md)`!` |
| [setNearLongitude](set-near-longitude.md) | `open fun setNearLongitude(nearLongitude: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Geocoder`](./index.md)`!` |

### Inheritors

| Name | Summary |
|---|---|
| [RegionalGeocoder](../-regional-geocoder/index.md) | `open class RegionalGeocoder : `[`Geocoder`](./index.md) |
