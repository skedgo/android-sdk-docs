[tripkit-android](../index.md) / [com.skedgo.tripkit.ui.timetables](./index.md)

## Package com.skedgo.tripkit.ui.timetables

### Types

| Name | Summary |
|---|---|
| [FetchAndLoadTimetable](-fetch-and-load-timetable/index.md) | `open class FetchAndLoadTimetable` |
| [FetchService](-fetch-service/index.md) | `class FetchService` |
| [FetchTimetable](-fetch-timetable/index.md) | `open class FetchTimetable` |
| [GetA2BTime](-get-a2-b-time/index.md) | `open class GetA2BTime` |
| [GetDirectionText](-get-direction-text/index.md) | `open class GetDirectionText` |
| [GetFrequencyText](-get-frequency-text/index.md) | `open class GetFrequencyText` |
| [GetOrdinaryTime](-get-ordinary-time/index.md) | `open class GetOrdinaryTime` |
| [GetRealtimeText](-get-realtime-text/index.md) | `open class GetRealtimeText` |
| [GetServiceSubTitleText](-get-service-sub-title-text/index.md) | `open class GetServiceSubTitleText` |
| [GetServiceTertiaryText](-get-service-tertiary-text/index.md) | `open class GetServiceTertiaryText` |
| [GetServiceTitleText](-get-service-title-text/index.md) | `open class GetServiceTitleText` |
| [GetTimeRangeText](-get-time-range-text/index.md) | `open class GetTimeRangeText` |
| [GetWheelchairAccessible](-get-wheelchair-accessible/index.md) | `open class GetWheelchairAccessible` |
| [JoinedCursor](-joined-cursor/index.md) | `class JoinedCursor : AbstractCursor` |
| [LoadServiceTask](-load-service-task/index.md) | `open class LoadServiceTask : `[`Callable`](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Callable.html)`<Pair<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`StopInfo`](../com.skedgo.tripkit.ui.model/-stop-info/index.md)`!>!, `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<ServiceLineInfo!>!>!>` |
| [LoadServiceTaskCursorCols](-load-service-task-cursor-cols/index.md) | TODO Should find an appropriate class name`open class LoadServiceTaskCursorCols` |
| [ServiceRepository](-service-repository/index.md) | `interface ServiceRepository` |
| [ServiceRepositoryImpl](-service-repository-impl/index.md) | `class ServiceRepositoryImpl : `[`ServiceRepository`](-service-repository/index.md) |
| [ServiceStopsLoaderFactory](-service-stops-loader-factory/index.md) | `open class ServiceStopsLoaderFactory` |
| [ServiceViewModel](-service-view-model/index.md) | `abstract class ServiceViewModel : `[`RxViewModel`](../com.skedgo.tripkit.ui.core/-rx-view-model/index.md) |
| [TimetableEntriesMapper](-timetable-entries-mapper/index.md) | `class TimetableEntriesMapper` |
| [TimetableFragment](-timetable-fragment/index.md) | `class TimetableFragment : `[`AbstractTripKitFragment`](../com.skedgo.tripkit.ui.core/-abstract-trip-kit-fragment/index.md)`, OnClickListener` |
| [TimetableViewModel](-timetable-view-model/index.md) | `class TimetableViewModel : `[`RxViewModel`](../com.skedgo.tripkit.ui.core/-rx-view-model/index.md) |

### Properties

| Name | Summary |
|---|---|
| [ARG_STOP](-a-r-g_-s-t-o-p.md) | `const val ARG_STOP: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ARG_TIMETABLE_ENTRY](-a-r-g_-t-i-m-e-t-a-b-l-e_-e-n-t-r-y.md) | `const val ARG_TIMETABLE_ENTRY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [getTimeLeftToDepartInterval](get-time-left-to-depart-interval.md) | `fun `[`TimetableEntry`](../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`.getTimeLeftToDepartInterval(period: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, timeUnit: `[`TimeUnit`](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/TimeUnit.html)`): Observable<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
| [realTimeArrival](real-time-arrival.md) | `fun realTimeArrival(service: `[`TimetableEntry`](../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`, vehicle: `[`RealTimeVehicle`](../com.skedgo.tripkit.routing/-real-time-vehicle/index.md)`? = null): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [realTimeDeparture](real-time-departure.md) | `fun realTimeDeparture(service: `[`TimetableEntry`](../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`, vehicle: `[`RealTimeVehicle`](../com.skedgo.tripkit.routing/-real-time-vehicle/index.md)`? = null): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [realTimeNotAvailable](real-time-not-available.md) | `fun realTimeNotAvailable(service: `[`TimetableEntry`](../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`, vehicle: `[`RealTimeVehicle`](../com.skedgo.tripkit.routing/-real-time-vehicle/index.md)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
