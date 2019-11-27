[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map.home](../index.md) / [ApiZoomLevels](./index.md)

# ApiZoomLevels

`class ApiZoomLevels`

Zoom level that is compatible with the locations.json API

### Properties

| Name | Summary |
|---|---|
| [LOCAL](-l-o-c-a-l.md) | Only non-parent stops (e.g, bus) are returned at this level.`static val LOCAL: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [REGION](-r-e-g-i-o-n.md) | Only parent stops (e.g, train) are returned at this level.`static val REGION: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [UNKNOWN](-u-n-k-n-o-w-n.md) | `static val UNKNOWN: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Functions

| Name | Summary |
|---|---|
| [fromMapZoomLevel](from-map-zoom-level.md) | Converts zoom level defined by Google map into zoom level compatible with the locations.json API.`static fun fromMapZoomLevel(zoomLevel: `[`ZoomLevel`](../-zoom-level/index.md)`!): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
