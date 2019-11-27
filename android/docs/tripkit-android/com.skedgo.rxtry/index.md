[tripkit-android](../index.md) / [com.skedgo.rxtry](./index.md)

## Package com.skedgo.rxtry

### Types

| Name | Summary |
|---|---|
| [Failure](-failure/index.md) | `data class Failure<T> : `[`Try`](-try.md)`<T>` |
| [Success](-success/index.md) | `data class Success<T> : `[`Try`](-try.md)`<T>` |
| [Try](-try.md) | `sealed class Try<T>` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [io.reactivex.Observable](io.reactivex.-observable/index.md) |  |
| [io.reactivex.Single](io.reactivex.-single/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [toTryObservable](to-try-observable.md) | Wraps any error from the upstream which matches [predicate](to-try-observable.md#com.skedgo.rxtry$toTryObservable(kotlin.Function1((kotlin.Throwable, kotlin.Boolean)))/predicate) into [Failure](-failure/index.md) while events emitted via [rx.Observer.onNext](#) will be wrapped into [Success](-success/index.md).`fun <T> toTryObservable(predicate: (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): ObservableTransformer<T, `[`Try`](-try.md)`<T>>`<br>Wraps any error from the upstream into [Failure](-failure/index.md) while events emitted via [rx.Observer.onNext](#) will be wrapped into [Success](-success/index.md).`fun <T> toTryObservable(): ObservableTransformer<T, `[`Try`](-try.md)`<T>>` |
| [toTrySingle](to-try-single.md) | Wraps any error from the upstream which matches [predicate](to-try-single.md#com.skedgo.rxtry$toTrySingle(kotlin.Function1((kotlin.Throwable, kotlin.Boolean)))/predicate) into [Failure](-failure/index.md) while events emitted via [rx.Observer.onNext](#) will be wrapped into [Success](-success/index.md).`fun <T> toTrySingle(predicate: (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): SingleTransformer<T, `[`Try`](-try.md)`<T>>`<br>Wraps any error from the upstream into [Failure](-failure/index.md) while events emitted via [rx.Observer.onNext](#) will be wrapped into [Success](-success/index.md).`fun <T> toTrySingle(): SingleTransformer<T, `[`Try`](-try.md)`<T>>` |
