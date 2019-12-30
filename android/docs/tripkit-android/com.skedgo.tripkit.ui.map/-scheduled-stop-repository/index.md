[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map](../index.md) / [ScheduledStopRepository](./index.md)

# ScheduledStopRepository

`@Singleton open class ScheduledStopRepository`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ScheduledStopRepository(dbHelper: `[`DbHelper`](../../com.skedgo.tripkit.data.database/-db-helper/index.md)`, cursorToStopConverter: `[`CursorToStopConverter`](../../com.skedgo.tripkit.ui.data/-cursor-to-stop-converter/index.md)`)` |

### Properties

| Name | Summary |
|---|---|
| [changes](changes.md) | `val changes: PublishRelay<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [cursorToStopConverter](cursor-to-stop-converter.md) | `val cursorToStopConverter: `[`CursorToStopConverter`](../../com.skedgo.tripkit.ui.data/-cursor-to-stop-converter/index.md) |
| [dbHelper](db-helper.md) | `val dbHelper: `[`DbHelper`](../../com.skedgo.tripkit.data.database/-db-helper/index.md) |

### Functions

| Name | Summary |
|---|---|
| [bulkInsert](bulk-insert.md) | `fun bulkInsert(contentValues: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<ContentValues>): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [delete](delete.md) | `fun delete(selection: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, selectionArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?): Completable` |
| [insertStops](insert-stops.md) | `fun insertStops(contentValues: ContentValues): Completable` |
| [notifyChange](notify-change.md) | `fun notifyChange(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [queryStops](query-stops.md) | `fun queryStops(projection: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?, selection: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, selectionArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?, order: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`ScheduledStop`](../../com.skedgo.tripkit.common.model/-scheduled-stop/index.md)`>>` |
| [queryStopsSync](query-stops-sync.md) | `fun queryStopsSync(projection: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?, selection: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, selectionArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?, order: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): Cursor` |
| [update](update.md) | `fun update(selection: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, selectionArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?, contentValues: ContentValues): Completable` |
