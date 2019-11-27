[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresult](../index.md) / [IsLocationPermissionGranted](index.md) / [invoke](./invoke.md)

# invoke

`open operator fun invoke(): Observable<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>`

Checks if given permission is granted or not. If it's granted, the returned signal
will emit true &amp; complete. Otherwise, waits until the permission is granted later.
Once it's granted, it will emit true but never complete.

