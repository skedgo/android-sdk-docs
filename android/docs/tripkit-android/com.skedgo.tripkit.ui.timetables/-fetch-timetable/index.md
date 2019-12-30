[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables](../index.md) / [FetchTimetable](./index.md)

# FetchTimetable

`open class FetchTimetable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FetchTimetable(departuresRepository: `[`DeparturesRepository`](../../com.skedgo.tripkit.ui.timetables.domain/-departures-repository/index.md)`, realtimeAlertRepository: RealtimeAlertRepository, parentStopDao: `[`ParentStopDao`](../../skedgo.tripgo.data.timetables/-parent-stop-dao/index.md)`, timetableEntriesMapper: `[`TimetableEntriesMapper`](../-timetable-entries-mapper/index.md)`, serviceAlertMapper: `[`ServiceAlertMapper`](../../com.skedgo.tripkit.data.database.timetables/-service-alert-mapper/index.md)`, serviceAlertsDao: `[`ServiceAlertsDao`](../../com.skedgo.tripkit.data.database.timetables/-service-alerts-dao/index.md)`, context: Context)` |

### Functions

| Name | Summary |
|---|---|
| [execute](execute.md) | `open fun execute(embarkationStopCodes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, region: `[`Region`](../../com.skedgo.tripkit.common.model/-region/index.md)`, startTimeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): Single<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`>, `[`Optional`](../../com.skedgo.tripkit.ui.utils/-optional/index.md)`<`[`ScheduledStop`](../../com.skedgo.tripkit.common.model/-scheduled-stop/index.md)`>>>` |
