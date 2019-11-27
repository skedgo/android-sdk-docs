[tripkit-android](../index.md) / [com.skedgo.tripkit.ui.map](./index.md)

## Package com.skedgo.tripkit.ui.map

### Types

| Name | Summary |
|---|---|
| [AlertMarkerIconFetcher](-alert-marker-icon-fetcher/index.md) | `open class AlertMarkerIconFetcher` |
| [AlertMarkerViewModel](-alert-marker-view-model/index.md) | `data class AlertMarkerViewModel` |
| [BaseMapFragment](-base-map-fragment/index.md) | `abstract class BaseMapFragment : `[`RxMapFragment`](../com.skedgo.tripkit.ui.core.rxlifecyclecomponents/-rx-map-fragment/index.md) |
| [BearingMarkerIconBuilder](-bearing-marker-icon-builder/index.md) | `open class BearingMarkerIconBuilder` |
| [BikePodPOILocation](-bike-pod-p-o-i-location/index.md) | `class BikePodPOILocation : `[`POILocation`](-p-o-i-location/index.md) |
| [CarPodPOILocation](-car-pod-p-o-i-location/index.md) | `class CarPodPOILocation : `[`POILocation`](-p-o-i-location/index.md) |
| [CreateMarkerForBikePod](-create-marker-for-bike-pod/index.md) | `object CreateMarkerForBikePod` |
| [CreateMarkerForCarPod](-create-marker-for-car-pod/index.md) | `object CreateMarkerForCarPod` |
| [CreateSegmentMarkers](-create-segment-markers/index.md) | `open class CreateSegmentMarkers` |
| [DefaultLoadPOILocationsByViewPort](-default-load-p-o-i-locations-by-view-port/index.md) | `class DefaultLoadPOILocationsByViewPort : `[`LoadPOILocationsByViewPort`](-load-p-o-i-locations-by-view-port/index.md) |
| [DefaultStopInfoWindowAdapter](-default-stop-info-window-adapter/index.md) | `class DefaultStopInfoWindowAdapter : `[`StopInfoWindowAdapter`](../com.skedgo.tripkit.ui.map.adapter/-stop-info-window-adapter/index.md) |
| [GetTripLine](-get-trip-line/index.md) | `open class GetTripLine` |
| [IconUtils](-icon-utils/index.md) | `class IconUtils` |
| [LoadBikePodsByViewPort](-load-bike-pods-by-view-port/index.md) | `open class LoadBikePodsByViewPort` |
| [LoadCarPodByViewPort](-load-car-pod-by-view-port/index.md) | `open class LoadCarPodByViewPort` |
| [LoadPOILocationsByViewPort](-load-p-o-i-locations-by-view-port/index.md) | `interface LoadPOILocationsByViewPort` |
| [LoadStopsByViewPort](-load-stops-by-view-port/index.md) | `open class LoadStopsByViewPort` |
| [LocationEnhancedMapFragment](-location-enhanced-map-fragment/index.md) | `open class LocationEnhancedMapFragment : `[`BaseMapFragment`](-base-map-fragment/index.md) |
| [MapCameraController](-map-camera-controller/index.md) | `class MapCameraController` |
| [MapMarkerUtils](-map-marker-utils/index.md) | `class MapMarkerUtils` |
| [MarkerTarget](-marker-target/index.md) | `open class MarkerTarget : Target` |
| [PinUpdateRepositoryImpl](-pin-update-repository-impl/index.md) | `class PinUpdateRepositoryImpl : PinUpdateRepository` |
| [POILocation](-p-o-i-location/index.md) | `interface POILocation` |
| [ScheduledStopRepository](-scheduled-stop-repository/index.md) | `open class ScheduledStopRepository` |
| [SegmentMarkerIconMaker](-segment-marker-icon-maker/index.md) | `class SegmentMarkerIconMaker` |
| [SegmentMarkerMaker](-segment-marker-maker/index.md) | `class SegmentMarkerMaker` |
| [SegmentStopMarkerMaker](-segment-stop-marker-maker/index.md) | `class SegmentStopMarkerMaker` |
| [ServiceAlertMarkerMaker](-service-alert-marker-maker/index.md) | `class ServiceAlertMarkerMaker` |
| [ServiceStop](-service-stop/index.md) | `data class ServiceStop` |
| [SimpleCalloutView](-simple-callout-view/index.md) | View to create custom callout in ``[`InfoWindowAdapter`](#), simply including a title, a snippet, a left image and a right image.`class SimpleCalloutView : LinearLayout` |
| [StopMarkerIconFetcher](-stop-marker-icon-fetcher/index.md) | `open class StopMarkerIconFetcher` |
| [StopMarkerViewModel](-stop-marker-view-model/index.md) | `data class StopMarkerViewModel` |
| [StopPOILocation](-stop-p-o-i-location/index.md) | `class StopPOILocation : `[`POILocation`](-p-o-i-location/index.md) |
| [TimeLabelMaker](-time-label-maker/index.md) | `open class TimeLabelMaker` |
| [TripLine](-trip-line.md) | `typealias TripLine = `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<PolylineOptions>` |
| [TripLocationMarkerCreator](-trip-location-marker-creator/index.md) | `open class TripLocationMarkerCreator` |
| [TripResultMapViewModel](-trip-result-map-view-model/index.md) | `class TripResultMapViewModel : `[`RxViewModel`](../com.skedgo.tripkit.ui.core/-rx-view-model/index.md) |
| [TripVehicleMarkerCreator](-trip-vehicle-marker-creator/index.md) | `open class TripVehicleMarkerCreator` |
| [VehicleMarkerIconCreator](-vehicle-marker-icon-creator/index.md) | `open class VehicleMarkerIconCreator` |
| [VehicleMarkerIconFetcher](-vehicle-marker-icon-fetcher/index.md) | `open class VehicleMarkerIconFetcher` |
| [VehicleMarkerViewModel](-vehicle-marker-view-model/index.md) | `data class VehicleMarkerViewModel` |

### Extensions for External Classes

| Name | Summary |
|---|---|
| [com.google.android.gms.maps.model.LatLngBounds](com.google.android.gms.maps.model.-lat-lng-bounds/index.md) |  |

### Functions

| Name | Summary |
|---|---|
| [createStopMarkerOptions](create-stop-marker-options.md) | `fun `[`ScheduledStop`](../com.skedgo.android.common.model/-scheduled-stop/index.md)`.createStopMarkerOptions(): Single<MarkerOptions>` |
| [getStopDisplayName](get-stop-display-name.md) | `fun `[`ScheduledStop`](../com.skedgo.android.common.model/-scheduled-stop/index.md)`.getStopDisplayName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
