[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map.home](../index.md) / [TripKitMapFragment](./index.md)

# TripKitMapFragment

`open class TripKitMapFragment : `[`LocationEnhancedMapFragment`](../../com.skedgo.tripkit.ui.map/-location-enhanced-map-fragment/index.md)`, OnInfoWindowClickListener, OnMapLongClickListener, OnCameraChangeListener, OnMarkerClickListener`

A map component for an app. It automatically integrates with SkedGo's backend, display transit information without any additional intervention. Being a fragment, it can very easily be added to an activity's layout. ```  ``` You **must** provide a TripGo API token as R.string.skedgo_api_key.

### Types

| Name | Summary |
|---|---|
| [OnInfoWindowClickListener](-on-info-window-click-listener/index.md) | When an icon in the map is clicked, an information window is displayed. When that information window is clicked, this interface is used as a callback to notify the app of the click.`interface OnInfoWindowClickListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | A map component for an app. It automatically integrates with SkedGo's backend, display transit information without any additional intervention. Being a fragment, it can very easily be added to an activity's layout. ```  ``` You **must** provide a TripGo API token as R.string.skedgo_api_key.`TripKitMapFragment()` |

### Functions

| Name | Summary |
|---|---|
| [animateToMyLocation](animate-to-my-location.md) | `open fun animateToMyLocation(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onAttach](on-attach.md) | `open fun onAttach(context: Context): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCameraChange](on-camera-change.md) | `open fun onCameraChange(position: CameraPosition!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreate](on-create.md) | `open fun onCreate(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onDestroy](on-destroy.md) | `open fun onDestroy(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onInfoWindowClick](on-info-window-click.md) | `open fun onInfoWindowClick(marker: Marker!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onLocationAddressDecoded](on-location-address-decoded.md) | `open fun onLocationAddressDecoded(locationTag: LocationTag!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onLocationSelected](on-location-selected.md) | `open fun onLocationSelected(locationTag: LocationTag!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onMapLongClick](on-map-long-click.md) | `open fun onMapLongClick(point: LatLng!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onMarkerClick](on-marker-click.md) | `open fun onMarkerClick(marker: Marker!): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onPause](on-pause.md) | `open fun onPause(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onResume](on-resume.md) | `open fun onResume(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setInfoWindowAdapter](set-info-window-adapter.md) | If we do not specify our own implementation, GoogleMap will fall back to its default implementation for InfoWindowAdapter.`open fun setInfoWindowAdapter(infoWindowAdapter: InfoWindowAdapter!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOnInfoWindowClickListener](set-on-info-window-click-listener.md) | `open fun setOnInfoWindowClickListener(listener: OnInfoWindowClickListener!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
