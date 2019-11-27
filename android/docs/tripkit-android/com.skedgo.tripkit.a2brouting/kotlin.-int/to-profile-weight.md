[tripkit-android](../../index.md) / [com.skedgo.tripkit.a2brouting](../index.md) / [kotlin.Int](index.md) / [toProfileWeight](./to-profile-weight.md)

# toProfileWeight

`fun `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`.toProfileWeight(): `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)

Weight values are stored in app as a value in range [0-100](#).
The server expects weights between 0.1 and 2.0. So we convert them.

**Receiver**
Value must be in range of 0 to 100.

**Return**
Corresponding value between 0.1 - 2.0.

