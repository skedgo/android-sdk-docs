[tripkit-android](../../index.md) / [com.skedgo.android.common.util](../index.md) / [PolyUtil](index.md) / [isLocationOnEdge](./is-location-on-edge.md)

# isLocationOnEdge

`open static fun isLocationOnEdge(point: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, polygon: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!, geodesic: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, tolerance: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Computes whether the given point lies on or near the edge of a polygon, within a specified tolerance in meters. The polygon edge is composed of great circle segments if geodesic is true, and of Rhumb segments otherwise. The polygon edge is implicitly closed -- the closing segment between the first point and the last point is included.

`open static fun isLocationOnEdge(point: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, polygon: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!, geodesic: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Same as ``[`#isLocationOnEdge(TripKitLatLng, List, boolean, double)`](./is-location-on-edge.md) with a default tolerance of 0.1 meters.

