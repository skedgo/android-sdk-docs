[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map](../index.md) / [CarPodPOILocation](./index.md)

# CarPodPOILocation

`class CarPodPOILocation : `[`POILocation`](../-p-o-i-location/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `CarPodPOILocation(carPod: `[`CarPod`](../../skedgo.tripkit.locations/-car-pod/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [identifier](identifier.md) | `val identifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [createMarkerOptions](create-marker-options.md) | `fun createMarkerOptions(resources: Resources, picasso: Picasso): Single<MarkerOptions>` |
| [getInfoWindowAdapter](get-info-window-adapter.md) | `fun getInfoWindowAdapter(context: Context): `[`StopInfoWindowAdapter`](../../com.skedgo.tripkit.ui.map.adapter/-stop-info-window-adapter/index.md)`?` |
| [onMarkerClick](on-marker-click.md) | `fun onMarkerClick(bus: Bus, eventTracker: EventTracker): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toLocation](to-location.md) | `fun toLocation(): `[`Location`](../../com.skedgo.android.common.model/-location/index.md) |
