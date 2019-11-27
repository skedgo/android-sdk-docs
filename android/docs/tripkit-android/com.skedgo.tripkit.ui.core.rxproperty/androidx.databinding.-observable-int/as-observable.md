[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.core.rxproperty](../index.md) / [androidx.databinding.ObservableInt](index.md) / [asObservable](./as-observable.md)

# asObservable

`fun ObservableInt.asObservable(): Observable<`[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>`

When we subscribe to an [Observable](#) created by this function,
the [Observable](#) will emit the current value of [ObservableInt](#)
and also emit any future changes.

