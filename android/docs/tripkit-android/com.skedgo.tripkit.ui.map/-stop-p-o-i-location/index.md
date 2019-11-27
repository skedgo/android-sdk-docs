[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map](../index.md) / [StopPOILocation](./index.md)

# StopPOILocation

`class StopPOILocation : `[`POILocation`](../-p-o-i-location/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `StopPOILocation(scheduledStop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`, stopInfoWindowAdapter: `[`StopInfoWindowAdapter`](../../com.skedgo.tripkit.ui.map.adapter/-stop-info-window-adapter/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [identifier](identifier.md) | `val identifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [scheduledStop](scheduled-stop.md) | `val scheduledStop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md) |

### Functions

| Name | Summary |
|---|---|
| [createMarkerOptions](create-marker-options.md) | `fun createMarkerOptions(resources: Resources, picasso: Picasso): Single<MarkerOptions>` |
| [getInfoWindowAdapter](get-info-window-adapter.md) | `fun getInfoWindowAdapter(context: Context): `[`StopInfoWindowAdapter`](../../com.skedgo.tripkit.ui.map.adapter/-stop-info-window-adapter/index.md)`?` |
| [onMarkerClick](on-marker-click.md) | `fun onMarkerClick(bus: Bus, eventTracker: EventTracker): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toLocation](to-location.md) | `fun toLocation(): `[`Location`](../../com.skedgo.android.common.model/-location/index.md) |
