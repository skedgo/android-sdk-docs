[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables](../index.md) / [FetchAndLoadTimetable](./index.md)

# FetchAndLoadTimetable

`open class FetchAndLoadTimetable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `FetchAndLoadTimetable(converter: `[`CursorToServiceConverter`](../../com.skedgo.tripkit.ui.data/-cursor-to-service-converter/index.md)`, parentStopDao: `[`ParentStopDao`](../../skedgo.tripgo.data.timetables/-parent-stop-dao/index.md)`, serviceAlertsDao: `[`ServiceAlertsDao`](../../com.skedgo.tripkit.data.database.timetables/-service-alerts-dao/index.md)`, serviceAlertsMapper: `[`ServiceAlertMapper`](../../com.skedgo.tripkit.data.database.timetables/-service-alert-mapper/index.md)`, context: Context, fetchTimetable: `[`FetchTimetable`](../-fetch-timetable/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [execute](execute.md) | `open fun execute(embarkationStopCodes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, region: `[`Region`](../../com.skedgo.android.common.model/-region/index.md)`, startTimeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): Single<`[`Pair`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-pair/index.html)`<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`>, `[`Optional`](../../com.skedgo.tripkit.ui.utils/-optional/index.md)`<`[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`>>>` |
