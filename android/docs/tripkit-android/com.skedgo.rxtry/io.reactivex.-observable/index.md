[tripkit-android](../../index.md) / [com.skedgo.rxtry](../index.md) / [io.reactivex.Observable](./index.md)

### Extensions for io.reactivex.Observable

| Name | Summary |
|---|---|
| [toTry](to-try.md) | Wraps any error from the upstream which matches [predicate](to-try.md#com.skedgo.rxtry$toTry(io.reactivex.Observable((com.skedgo.rxtry.toTry.T)), kotlin.Function1((kotlin.Throwable, kotlin.Boolean)))/predicate) into [Failure](../-failure/index.md) while events emitted via [rx.Observer.onNext](#) will be wrapped into [Success](../-success/index.md).`fun <T> Observable<T>.toTry(predicate: (`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`) -> `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = { true }): Observable<`[`Try`](../-try.md)`<T>>` |
