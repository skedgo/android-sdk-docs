[tripkit-android](../../index.md) / [com.skedgo.android.common.util](../index.md) / [PolyUtil](index.md) / [isClosedPolygon](./is-closed-polygon.md)

# isClosedPolygon

`open static fun isClosedPolygon(poly: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitLatLng`](../-trip-kit-lat-lng/index.md)`!>!): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)

Returns true if the provided list of points is a closed polygon (i.e., the first and last points are the same), and false if it is not

### Parameters

`poly` - [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[TripKitLatLng](../-trip-kit-lat-lng/index.md)!&gt;!: polyline or polygon

**Return**
[Boolean](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html): true if the provided list of points is a closed polygon (i.e., the first and last points are the same), and false if it is not

