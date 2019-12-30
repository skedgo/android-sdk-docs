[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.provider](../index.md) / [TimetableProvider](./index.md)

# TimetableProvider

`class TimetableProvider : ContentProvider`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TimetableProvider()` |

### Properties

| Name | Summary |
|---|---|
| [mDbHelper](m-db-helper.md) | `lateinit var mDbHelper: `[`DbHelper`](../../com.skedgo.tripkit.data.database/-db-helper/index.md) |
| [scheduledServiceRealtimeInfoDao](scheduled-service-realtime-info-dao.md) | `lateinit var scheduledServiceRealtimeInfoDao: `[`ScheduledServiceRealtimeInfoDao`](../../com.skedgo.tripkit.data.database.timetables/-scheduled-service-realtime-info-dao/index.md) |

### Functions

| Name | Summary |
|---|---|
| [bulkInsert](bulk-insert.md) | `fun bulkInsert(uri: Uri, values: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<ContentValues>): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [delete](delete.md) | `fun delete(uri: Uri, sel: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, selArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getType](get-type.md) | `fun getType(uri: Uri): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [insert](insert.md) | `fun insert(uri: Uri, values: ContentValues?): Uri?` |
| [onCreate](on-create.md) | `fun onCreate(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [query](query.md) | `fun query(uri: Uri, projection: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?, selection: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, selectionArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?, sortOrder: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): Cursor?` |
| [update](update.md) | `fun update(uri: Uri, values: ContentValues?, sel: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, selArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [AUTHORITY](-a-u-t-h-o-r-i-t-y.md) | `val AUTHORITY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [REMINDERS_URI](-r-e-m-i-n-d-e-r-s_-u-r-i.md) | `val REMINDERS_URI: Uri!` |
| [SCHEDULED_SERVICES_URI](-s-c-h-e-d-u-l-e-d_-s-e-r-v-i-c-e-s_-u-r-i.md) | `val SCHEDULED_SERVICES_URI: Uri!` |
| [SERVICE_ALERT_URI](-s-e-r-v-i-c-e_-a-l-e-r-t_-u-r-i.md) | `val SERVICE_ALERT_URI: Uri!` |
