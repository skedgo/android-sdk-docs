[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map.servicestop](../index.md) / [ServiceStopMapViewModel](./index.md)

# ServiceStopMapViewModel

`class ServiceStopMapViewModel : `[`RxViewModel`](../../com.skedgo.tripkit.ui.core/-rx-view-model/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServiceStopMapViewModel(context: Context, fetchAndLoadServices: `[`FetchAndLoadServices`](../../com.skedgo.tripkit.ui.servicedetail/-fetch-and-load-services/index.md)`, regionService: `[`RegionService`](../../com.skedgo.tripkit.data.regions/-region-service/index.md)`, getStopDisplayText: `[`GetStopDisplayText`](../../com.skedgo.tripkit.ui.servicedetail/-get-stop-display-text/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [context](context.md) | `val context: Context` |
| [drawServiceLine](draw-service-line.md) | `val drawServiceLine: Observable<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<PolylineOptions!>!>` |
| [drawStops](draw-stops.md) | `val drawStops: Observable<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<MarkerOptions, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>>, `[`Set`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-set/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>>!>` |
| [fetchAndLoadServices](fetch-and-load-services.md) | `val fetchAndLoadServices: `[`FetchAndLoadServices`](../../com.skedgo.tripkit.ui.servicedetail/-fetch-and-load-services/index.md) |
| [getStopDisplayText](get-stop-display-text.md) | `val getStopDisplayText: `[`GetStopDisplayText`](../../com.skedgo.tripkit.ui.servicedetail/-get-stop-display-text/index.md) |
| [realtimeVehicle](realtime-vehicle.md) | `val realtimeVehicle: Observable<Optional<`[`RealTimeVehicle`](../../com.skedgo.tripkit.routing/-real-time-vehicle/index.md)`>!>` |
| [realtimeViewModel](realtime-view-model.md) | `lateinit var realtimeViewModel: `[`RealTimeChoreographerViewModel`](../../com.skedgo.tripkit.ui.realtime/-real-time-choreographer-view-model/index.md) |
| [region](region.md) | `val region: Observable<`[`Region`](../../com.skedgo.tripkit.common.model/-region/index.md)`!>` |
| [regionService](region-service.md) | `val regionService: `[`RegionService`](../../com.skedgo.tripkit.data.regions/-region-service/index.md) |
| [service](service.md) | `val service: BehaviorRelay<`[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`!>` |
| [serviceStopMarkerCreator](service-stop-marker-creator.md) | `lateinit var serviceStopMarkerCreator: `[`ServiceStopMarkerCreator`](../-service-stop-marker-creator/index.md) |
| [stop](stop.md) | `val stop: BehaviorRelay<`[`ScheduledStop`](../../com.skedgo.tripkit.common.model/-scheduled-stop/index.md)`!>` |
| [viewPort](view-port.md) | `val viewPort: Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<LatLng>!>` |
