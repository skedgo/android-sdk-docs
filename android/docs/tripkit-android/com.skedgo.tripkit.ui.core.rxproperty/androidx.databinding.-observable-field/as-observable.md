[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.core.rxproperty](../index.md) / [androidx.databinding.ObservableField](index.md) / [asObservable](./as-observable.md)

# asObservable

`fun <T> ObservableField<T>.asObservable(): Observable<T>`

When we subscribe to an [Observable](#) created by this function,
the [Observable](#) will emit the current value of [ObservableField](#)
and also emit any future changes.

