[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map](../index.md) / [POILocation](./index.md)

# POILocation

`interface POILocation`

### Properties

| Name | Summary |
|---|---|
| [identifier](identifier.md) | `abstract val identifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [createMarkerOptions](create-marker-options.md) | `abstract fun createMarkerOptions(resources: Resources, picasso: Picasso): Single<MarkerOptions>` |
| [getInfoWindowAdapter](get-info-window-adapter.md) | `abstract fun getInfoWindowAdapter(context: Context): `[`StopInfoWindowAdapter`](../../com.skedgo.tripkit.ui.map.adapter/-stop-info-window-adapter/index.md)`?` |
| [onMarkerClick](on-marker-click.md) | `abstract fun onMarkerClick(bus: Bus, eventTracker: EventTracker): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toLocation](to-location.md) | `abstract fun toLocation(): `[`Location`](../../com.skedgo.tripkit.common.model/-location/index.md) |

### Inheritors

| Name | Summary |
|---|---|
| [BikePodPOILocation](../-bike-pod-p-o-i-location/index.md) | `class BikePodPOILocation : `[`POILocation`](./index.md) |
| [CarPodPOILocation](../-car-pod-p-o-i-location/index.md) | `class CarPodPOILocation : `[`POILocation`](./index.md) |
| [StopPOILocation](../-stop-p-o-i-location/index.md) | `class StopPOILocation : `[`POILocation`](./index.md) |
