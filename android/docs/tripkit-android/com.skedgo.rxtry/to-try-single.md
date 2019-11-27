[tripkit-android](../index.md) / [com.skedgo.rxtry](index.md) / [toTrySingle](./to-try-single.md)

# toTrySingle

`fun <T> toTrySingle(predicate: (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): SingleTransformer<T, `[`Try`](-try.md)`<T>>`

Wraps any error from the upstream which matches [predicate](to-try-single.md#com.skedgo.rxtry$toTrySingle(kotlin.Function1((kotlin.Throwable, kotlin.Boolean)))/predicate) into [Failure](-failure/index.md) while
events emitted via [rx.Observer.onNext](#) will be wrapped into [Success](-success/index.md).

`fun <T> toTrySingle(): SingleTransformer<T, `[`Try`](-try.md)`<T>>`

Wraps any error from the upstream into [Failure](-failure/index.md) while
events emitted via [rx.Observer.onNext](#) will be wrapped into [Success](-success/index.md).

