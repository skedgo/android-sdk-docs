[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map.servicestop](../index.md) / [ServiceStopMapFragment](./index.md)

# ServiceStopMapFragment

`open class ServiceStopMapFragment : `[`LocationEnhancedMapFragment`](../../com.skedgo.tripkit.ui.map/-location-enhanced-map-fragment/index.md)`, OnInfoWindowClickListener, InfoWindowAdapter, OnTimetableEntrySelectedListener, OnScheduledStopClickListener`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServiceStopMapFragment()` |

### Functions

| Name | Summary |
|---|---|
| [getInfoContents](get-info-contents.md) | `open fun getInfoContents(marker: Marker!): View!` |
| [getInfoWindow](get-info-window.md) | `open fun getInfoWindow(marker: Marker!): View!` |
| [onActivityCreated](on-activity-created.md) | `open fun onActivityCreated(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreate](on-create.md) | `open fun onCreate(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onDestroy](on-destroy.md) | `open fun onDestroy(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onInfoWindowClick](on-info-window-click.md) | `open fun onInfoWindowClick(marker: Marker!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onScheduledStopClicked](on-scheduled-stop-clicked.md) | `open fun onScheduledStopClicked(stop: `[`ServiceStop`](../../com.skedgo.android.common.model/-service-stop/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStart](on-start.md) | `open fun onStart(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStop](on-stop.md) | `open fun onStop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onTimetableEntrySelected](on-timetable-entry-selected.md) | `open fun onTimetableEntrySelected(service: `[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`, stop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`, minStartTime: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setService](set-service.md) | `open fun setService(service: `[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStop](set-stop.md) | `open fun setStop(stop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
