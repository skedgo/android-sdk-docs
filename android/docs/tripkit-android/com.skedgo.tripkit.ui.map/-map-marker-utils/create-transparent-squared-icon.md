[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map](../index.md) / [MapMarkerUtils](index.md) / [createTransparentSquaredIcon](./create-transparent-squared-icon.md)

# createTransparentSquaredIcon

`static fun createTransparentSquaredIcon(@NonNull res: Resources, @DimenRes sizeResId: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): BitmapDescriptor!`

This replaces the old solution that use a transparent bitmap contained in the drawable/ folder. The advantage is that, this creates a bitmap that looks more consistent over various DPIs.

