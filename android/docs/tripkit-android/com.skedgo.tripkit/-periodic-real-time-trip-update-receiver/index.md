[tripkit-android](../../index.md) / [com.skedgo.tripkit](../index.md) / [PeriodicRealTimeTripUpdateReceiver](./index.md)

# PeriodicRealTimeTripUpdateReceiver

`@Immutable abstract class PeriodicRealTimeTripUpdateReceiver : `[`RealTimeTripUpdateReceiver`](../-real-time-trip-update-receiver/index.md)

### Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | `interface Builder` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PeriodicRealTimeTripUpdateReceiver()` |

### Functions

| Name | Summary |
|---|---|
| [builder](builder.md) | `open static fun builder(): Builder!` |
| [startAsync](start-async.md) | `open fun startAsync(): Flowable<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`Trip`](../../skedgo.tripkit.routing/-trip/index.md)`!, `[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`!>!>!` |
| [stop](stop.md) | `open fun stop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
