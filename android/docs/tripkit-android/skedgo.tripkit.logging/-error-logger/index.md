[tripkit-android](../../index.md) / [skedgo.tripkit.logging](../index.md) / [ErrorLogger](./index.md)

# ErrorLogger

`interface ErrorLogger`

### Functions

| Name | Summary |
|---|---|
| [logError](log-error.md) | Just prints the error out for the sake of debugging.`abstract fun logError(error: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [trackError](track-error.md) | If debuggable, it just simply prints the error out. Otherwise, it'll upload that error to Fabric for further investigation. Should use this to catch some errors that we may not be aware of.`abstract fun trackError(error: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [ErrorLoggerImpl](../../com.skedgo.tripkit.ui.core/-error-logger-impl/index.md) | `class ErrorLoggerImpl : `[`ErrorLogger`](./index.md) |
