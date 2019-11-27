[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map](../index.md) / [TripResultMapViewModel](./index.md)

# TripResultMapViewModel

`class TripResultMapViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Properties

| Name | Summary |
|---|---|
| [alertMarkerViewModels](alert-marker-view-models.md) | `val alertMarkerViewModels: Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`AlertMarkerViewModel`](../-alert-marker-view-model/index.md)`>>` |
| [nonTravelledStopMarkerViewModels](non-travelled-stop-marker-view-models.md) | `val nonTravelledStopMarkerViewModels: Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`StopMarkerViewModel`](../-stop-marker-view-model/index.md)`>>` |
| [segments](segments.md) | `val segments: Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TripSegment`](../../skedgo.tripkit.routing/-trip-segment/index.md)`>>` |
| [travelledStopMarkerViewModels](travelled-stop-marker-view-models.md) | `val travelledStopMarkerViewModels: Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`StopMarkerViewModel`](../-stop-marker-view-model/index.md)`>>` |
| [tripCameraUpdate](trip-camera-update.md) | `val tripCameraUpdate: Observable<`[`MapCameraUpdate`](../../com.skedgo.tripkit.ui.tripresult/-map-camera-update/index.md)`>` |
| [vehicleMarkerViewModels](vehicle-marker-view-models.md) | `val vehicleMarkerViewModels: Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`VehicleMarkerViewModel`](../-vehicle-marker-view-model/index.md)`>>` |

### Functions

| Name | Summary |
|---|---|
| [getCameraUpdate](get-camera-update.md) | `fun getCameraUpdate(): CameraUpdate?` |
| [onTripSegmentTapped](on-trip-segment-tapped.md) | `fun onTripSegmentTapped(): Observable<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<CameraUpdate, `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>>` |
| [setTripGroupId](set-trip-group-id.md) | `fun setTripGroupId(tripGroupId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
