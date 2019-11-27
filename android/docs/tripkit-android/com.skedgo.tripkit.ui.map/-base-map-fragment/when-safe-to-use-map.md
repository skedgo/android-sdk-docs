[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map](../index.md) / [BaseMapFragment](index.md) / [whenSafeToUseMap](./when-safe-to-use-map.md)

# whenSafeToUseMap

`fun whenSafeToUseMap(callback: Consumer<GoogleMap>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

A safer point to retrieve [GoogleMap](#) as the callback is invoked
after fragment view is measured. This makes it safe to move or animate map with CameraUpdate.

