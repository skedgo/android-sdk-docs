[tripkit-android](../../index.md) / [com.skedgo.android.common.util](../index.md) / [PolyUtil](index.md) / [isLocationOnPath](./is-location-on-path.md)

# isLocationOnPath

`open static fun isLocationOnPath(point: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, polyline: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!, geodesic: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, tolerance: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Computes whether the given point lies on or near a polyline, within a specified tolerance in meters. The polyline is composed of great circle segments if geodesic is true, and of Rhumb segments otherwise. The polyline is not closed -- the closing segment between the first point and the last point is not included.

`open static fun isLocationOnPath(point: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, polyline: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!, geodesic: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Same as ``[`#isLocationOnPath(TripKitLatLng, List, boolean, double)`](./is-location-on-path.md)

 with a default tolerance of 0.1 meters.

