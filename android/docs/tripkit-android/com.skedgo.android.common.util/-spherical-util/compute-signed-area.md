[tripkit-android](../../index.md) / [com.skedgo.android.common.util](../index.md) / [SphericalUtil](index.md) / [computeSignedArea](./compute-signed-area.md)

# computeSignedArea

`open static fun computeSignedArea(path: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)

Returns the signed area of a closed path on Earth. The sign of the area may be used to determine the orientation of the path. "inside" is the surface that does not contain the South Pole.

### Parameters

`path` - [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[TripKitLatLng](../-trip-kit-lat-lng/index.md)!&gt;!: A closed path.

**Return**
[Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html): The loop's area in square meters.

