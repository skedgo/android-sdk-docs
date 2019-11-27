[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables.domain](../index.md) / [TimetableLoaderFactory](./index.md)

# TimetableLoaderFactory

`class TimetableLoaderFactory`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TimetableLoaderFactory()` |

### Functions

| Name | Summary |
|---|---|
| [createForSegment](create-for-segment.md) | Creates a loader which is used to load A2B timetable from database.`fun createForSegment(context: Context, pairIdentifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, sinceSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): CursorLoader` |

### Companion Object Functions

| Name | Summary |
|---|---|
| [buildQueryParams](build-query-params.md) | `fun buildQueryParams(stopCodes: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>, sinceSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`TimetableQueryParams`](../-timetable-query-params/index.md)<br>`fun buildQueryParams(stop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`, filter: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, sinceSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`TimetableQueryParams`](../-timetable-query-params/index.md) |
| [createForStop](create-for-stop.md) | `fun createForStop(appContext: Context, stop: `[`ScheduledStop`](../../com.skedgo.android.common.model/-scheduled-stop/index.md)`, filter: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, sinceSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): Loader<Cursor>` |
