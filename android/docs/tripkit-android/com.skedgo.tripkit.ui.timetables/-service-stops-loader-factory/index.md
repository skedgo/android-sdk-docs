[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables](../index.md) / [ServiceStopsLoaderFactory](./index.md)

# ServiceStopsLoaderFactory

`open class ServiceStopsLoaderFactory`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServiceStopsLoaderFactory()` |

### Properties

| Name | Summary |
|---|---|
| [PROJECTION](-p-r-o-j-e-c-t-i-o-n.md) | `static val PROJECTION: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!` |
| [SELECTION](-s-e-l-e-c-t-i-o-n.md) | segment_shapes.service_trip_id = ? AND (service_stops.julian_day = ? OR service_stops.julian_day = 0)`static val SELECTION: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [SORT_ORDER](-s-o-r-t_-o-r-d-e-r.md) | service_stops.arrival_time ASC, service_stops.departure_time ASC`static val SORT_ORDER: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |

### Functions

| Name | Summary |
|---|---|
| [create](create.md) | `open static fun create(context: Context!, serviceTripId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, timeInSeconds: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): CursorLoader!` |
