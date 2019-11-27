[tripkit-android](../../index.md) / [com.skedgo.geocoding](../index.md) / [GCBoundingBox](./index.md)

# GCBoundingBox

`open class GCBoundingBox : `[`GCBoundingBoxInterface`](../../com.skedgo.geocoding.agregator/-g-c-bounding-box-interface/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `GCBoundingBox(lat1: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lat2: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lng1: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lng2: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`)`<br>`GCBoundingBox(bb: `[`GCBoundingBoxInterface`](../../com.skedgo.geocoding.agregator/-g-c-bounding-box-interface/index.md)`!)`<br>`GCBoundingBox(other: `[`GCBoundingBox`](./index.md)`!)` |

### Properties

| Name | Summary |
|---|---|
| [lat1](lat1.md) | `var lat1: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [lat2](lat2.md) | `var lat2: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [lng1](lng1.md) | `var lng1: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [lng2](lng2.md) | `var lng2: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [World](-world.md) | `static val World: `[`GCBoundingBox`](./index.md)`!` |

### Functions

| Name | Summary |
|---|---|
| [center](center.md) | `open fun center(): `[`LatLng`](../-lat-lng/index.md)`!` |
| [getBoundingBox](get-bounding-box.md) | `open fun getBoundingBox(): `[`GCBoundingBox`](./index.md)`!` |
| [getLatitudeDelta](get-latitude-delta.md) | `open fun getLatitudeDelta(): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getLatLngs](get-lat-lngs.md) | `open fun getLatLngs(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`LatLng`](../-lat-lng/index.md)`!>!` |
| [getLatN](get-lat-n.md) | `open fun getLatN(): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getLatS](get-lat-s.md) | `open fun getLatS(): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getLngE](get-lng-e.md) | `open fun getLngE(): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getLngW](get-lng-w.md) | `open fun getLngW(): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getLongitudeDelta](get-longitude-delta.md) | `open fun getLongitudeDelta(): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [height](height.md) | `open fun height(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
