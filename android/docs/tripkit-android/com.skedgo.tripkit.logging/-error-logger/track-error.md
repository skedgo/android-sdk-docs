[tripkit-android](../../index.md) / [com.skedgo.tripkit.logging](../index.md) / [ErrorLogger](index.md) / [trackError](./track-error.md)

# trackError

`abstract fun trackError(error: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

If debuggable, it just simply prints the error out.
Otherwise, it'll upload that error to Fabric for further investigation.
Should use this to catch some errors that we may not be aware of.

