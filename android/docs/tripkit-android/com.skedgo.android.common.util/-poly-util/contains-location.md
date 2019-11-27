[tripkit-android](../../index.md) / [com.skedgo.android.common.util](../index.md) / [PolyUtil](index.md) / [containsLocation](./contains-location.md)

# containsLocation

`open static fun containsLocation(point: `[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!, polygon: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!, geodesic: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`open static fun containsLocation(latitude: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, longitude: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, polygon: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!, geodesic: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Computes whether the given point lies inside the specified polygon. The polygon is always considered closed, regardless of whether the last point equals the first or not. Inside is defined as not containing the South Pole -- the South Pole is always outside. The polygon is formed of great circle segments if geodesic is true, and of rhumb (loxodromic) segments otherwise.

