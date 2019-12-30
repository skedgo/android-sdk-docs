[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.util](../index.md) / [PolyUtil](index.md) / [locationIndexOnPath](./location-index-on-path.md)

# locationIndexOnPath

`open static fun locationIndexOnPath(point: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, poly: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!, geodesic: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, tolerance: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

Computes whether (and where) a given point lies on or near a polyline, within a specified tolerance. The polyline is not closed -- the closing segment between the first point and the last point is not included.

### Parameters

`point` - [TripKitLatLng](../-trip-kit-lat-lng/index.md)!: our needle

`poly` - [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[TripKitLatLng](../-trip-kit-lat-lng/index.md)!&gt;!: our haystack

`geodesic` - [Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html): the polyline is composed of great circle segments if geodesic is true, and of Rhumb segments otherwise

`tolerance` - [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html): tolerance (in meters)

**Return**
[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html): -1 if point does not lie on or near the polyline. 0 if point is between poly[0] and poly[1] (inclusive), 1 if between poly[1] and poly[2], ..., poly.size()-2 if between poly[poly.size() - 2] and poly[poly.size() - 1]

`open static fun locationIndexOnPath(point: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, polyline: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!, geodesic: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

Same as ``[`#locationIndexOnPath(TripKitLatLng, List, boolean, double)`](./location-index-on-path.md)

 with a default tolerance of 0.1 meters.

