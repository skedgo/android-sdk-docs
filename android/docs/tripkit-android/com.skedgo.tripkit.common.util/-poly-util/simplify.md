[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.util](../index.md) / [PolyUtil](index.md) / [simplify](./simplify.md)

# simplify

`open static fun simplify(poly: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!, tolerance: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!`

Simplifies the given poly (polyline or polygon) using the Douglas-Peucker decimation algorithm. Increasing the tolerance will result in fewer points in the simplified polyline or polygon.

 When the providing a polygon as input, the first and last point of the list MUST have the same latitude and longitude (i.e., the polygon must be closed). If the input polygon is not closed, the resulting polygon may not be fully simplified.

 The time complexity of Douglas-Peucker is O(n^2), so take care that you do not call this algorithm too frequently in your code.

### Parameters

`poly` - [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[TripKitLatLng](../-trip-kit-lat-lng/index.md)!&gt;!: polyline or polygon to be simplified. Polygon should be closed (i.e., first and last points should have the same latitude and longitude).

`tolerance` - [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html): in meters. Increasing the tolerance will result in fewer points in the simplified poly.

**Return**
[MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[TripKitLatLng](../-trip-kit-lat-lng/index.md)!&gt;!: a simplified poly produced by the Douglas-Peucker algorithm

