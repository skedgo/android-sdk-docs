[tripkit-android](../../index.md) / [com.skedgo.android.common.util](../index.md) / [PolyUtil](index.md) / [locationIndexOnEdgeOrPath](./location-index-on-edge-or-path.md)

# locationIndexOnEdgeOrPath

`open static fun locationIndexOnEdgeOrPath(point: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, poly: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!, closed: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, geodesic: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, toleranceEarth: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

Computes whether (and where) a given point lies on or near a polyline, within a specified tolerance. If closed, the closing segment between the last and first points of the polyline is not considered.

### Parameters

`point` - [TripKitLatLng](../-trip-kit-lat-lng/index.md)!: our needle

`poly` - [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[TripKitLatLng](../-trip-kit-lat-lng/index.md)!&gt;!: our haystack

`closed` - [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html): whether the polyline should be considered closed by a segment connecting the last point back to the first one

`geodesic` - [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html): the polyline is composed of great circle segments if geodesic is true, and of Rhumb segments otherwise

`toleranceEarth` - [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html): tolerance (in meters)

**Return**
[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html): -1 if point does not lie on or near the polyline. 0 if point is between poly[0] and poly[1] (inclusive), 1 if between poly[1] and poly[2], ..., poly.size()-2 if between poly[poly.size() - 2] and poly[poly.size() - 1]

