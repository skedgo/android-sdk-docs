[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map.home](../index.md) / [MapViewModel](./index.md)

# MapViewModel

`class MapViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Properties

| Name | Summary |
|---|---|
| [markers](markers.md) | `val markers: Observable<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<MarkerOptions, `[`POILocation`](../../com.skedgo.tripkit.ui.map/-p-o-i-location/index.md)`>>, `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>>!>` |
| [myLocation](my-location.md) | `val myLocation: Observable<`[`Location`](../../com.skedgo.tripkit.common.model/-location/index.md)`>` |
| [myLocationError](my-location-error.md) | `val myLocationError: Observable<`[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [getDestinationPinUpdate](get-destination-pin-update.md) | `fun getDestinationPinUpdate(): Observable<PinUpdate>` |
| [getInitialCameraUpdate](get-initial-camera-update.md) | `fun getInitialCameraUpdate(requestLocationPermission: () -> Observable<`[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`> = { Observable.just(true) }): Observable<CameraUpdate>` |
| [getOriginPinUpdate](get-origin-pin-update.md) | `fun getOriginPinUpdate(): Observable<PinUpdate>` |
| [goToMyLocation](go-to-my-location.md) | `fun goToMyLocation(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onViewPortChanged](on-view-port-changed.md) | `fun onViewPortChanged(viewPort: `[`ViewPort`](../-view-port/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [putCameraPosition](put-camera-position.md) | `fun putCameraPosition(cameraPosition: CameraPosition?): Completable` |
