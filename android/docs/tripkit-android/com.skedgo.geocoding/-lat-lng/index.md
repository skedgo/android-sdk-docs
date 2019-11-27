[tripkit-android](../../index.md) / [com.skedgo.geocoding](../index.md) / [LatLng](./index.md)

# LatLng

`open class LatLng`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LatLng()`<br>`LatLng(_lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, _lng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`)`<br>`LatLng(other: `[`LatLng`](./index.md)`!)` |

### Properties

| Name | Summary |
|---|---|
| [EarthRadius](-earth-radius.md) | `static val EarthRadius: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [lat](lat.md) | `var lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [lng](lng.md) | `var lng: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [NO_NUM](-n-o_-n-u-m.md) | `static val NO_NUM: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [nullLatLong](null-lat-long.md) | `static var nullLatLong: `[`LatLng`](./index.md) |
| [radians](radians.md) | `static val radians: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

### Functions

| Name | Summary |
|---|---|
| [distanceInMetres](distance-in-metres.md) | This is the Equirectangular approximation. It's a little slower than the Region.distanceInMetres() formula.`open fun distanceInMetres(other: `[`LatLng`](./index.md)`!): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
