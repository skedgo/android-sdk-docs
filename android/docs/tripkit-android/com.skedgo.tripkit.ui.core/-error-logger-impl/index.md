[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.core](../index.md) / [ErrorLoggerImpl](./index.md)

# ErrorLoggerImpl

`class ErrorLoggerImpl : `[`ErrorLogger`](../../skedgo.tripkit.logging/-error-logger/index.md)

### Functions

| Name | Summary |
|---|---|
| [logError](log-error.md) | Just prints the error out for the sake of debugging.`fun logError(error: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [trackError](track-error.md) | If debuggable, it just simply prints the error out. Otherwise, it'll upload that error to Fabric for further investigation. Should use this to catch some errors that we may not be aware of.`fun trackError(error: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
