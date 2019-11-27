[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.core.rxproperty](../index.md) / [androidx.databinding.ObservableBoolean](index.md) / [asObservable](./as-observable.md)

# asObservable

`fun ObservableBoolean.asObservable(): Observable<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>`

When we subscribe to an [Observable](#) created by this function,
the [Observable](#) will emit the current value of [ObservableBoolean](#)
and also emit any future changes.

