[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.core](../index.md) / [Converters](index.md) / [convertBooleanToViewVisibility](./convert-boolean-to-view-visibility.md)

# convertBooleanToViewVisibility

`static fun convertBooleanToViewVisibility(value: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

Binds a boolean into ``[`View#setVisibility(int)`](#). Sample: `android:visibility="@{viewModel.isBusy}` `isBusy` can be an ``[`ObservableBoolean`](#).

