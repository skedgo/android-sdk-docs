[tripkit-android](../index.md) / [com.skedgo.rxtry](index.md) / [toTryObservable](./to-try-observable.md)

# toTryObservable

`fun <T> toTryObservable(predicate: (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): ObservableTransformer<T, `[`Try`](-try.md)`<T>>`

Wraps any error from the upstream which matches [predicate](to-try-observable.md#com.skedgo.rxtry$toTryObservable(kotlin.Function1((kotlin.Throwable, kotlin.Boolean)))/predicate) into [Failure](-failure/index.md) while
events emitted via [rx.Observer.onNext](#) will be wrapped into [Success](-success/index.md).

`fun <T> toTryObservable(): ObservableTransformer<T, `[`Try`](-try.md)`<T>>`

Wraps any error from the upstream into [Failure](-failure/index.md) while
events emitted via [rx.Observer.onNext](#) will be wrapped into [Success](-success/index.md).

