[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.realtime](../index.md) / [RealTimeChoreographerViewModel](./index.md)

# RealTimeChoreographerViewModel

`class RealTimeChoreographerViewModel : ViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RealTimeChoreographerViewModel(realTimeChoreographer: `[`RealTimeChoreographer`](../-real-time-choreographer/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [getRealTimeVehicles](get-real-time-vehicles.md) | `fun getRealTimeVehicles(region: `[`Region`](../../com.skedgo.android.common.model/-region/index.md)`, services: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`IRealTimeElement`](../../com.skedgo.android.common.agenda/-i-real-time-element/index.md)`>): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RealTimeVehicle`](../../skedgo.tripkit.routing/-real-time-vehicle/index.md)`>>` |
| [realTimeVehicleObservable](real-time-vehicle-observable.md) | `fun realTimeVehicleObservable(service: `[`IRealTimeElement`](../../com.skedgo.android.common.agenda/-i-real-time-element/index.md)`): Observable<`[`RealTimeVehicle`](../../skedgo.tripkit.routing/-real-time-vehicle/index.md)`>` |
