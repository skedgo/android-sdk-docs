[tripkit-android](../../index.md) / [com.skedgo.tripkit](../index.md) / [RealTimeTripUpdateReceiver](./index.md)

# RealTimeTripUpdateReceiver

`interface RealTimeTripUpdateReceiver`

### Functions

| Name | Summary |
|---|---|
| [startAsync](start-async.md) | `abstract fun startAsync(): Flowable<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Trip`](../../skedgo.tripkit.routing/-trip/index.md)`!, `[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`!>!>!` |
| [stop](stop.md) | `abstract fun stop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [PeriodicRealTimeTripUpdateReceiver](../-periodic-real-time-trip-update-receiver/index.md) | `abstract class PeriodicRealTimeTripUpdateReceiver : `[`RealTimeTripUpdateReceiver`](./index.md) |
