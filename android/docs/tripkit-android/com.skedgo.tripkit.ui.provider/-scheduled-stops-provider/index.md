[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.provider](../index.md) / [ScheduledStopsProvider](./index.md)

# ScheduledStopsProvider

`open class ScheduledStopsProvider : ContentProvider`

**Author**
Daniel Grech

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ScheduledStopsProvider()` |

### Properties

| Name | Summary |
|---|---|
| [AUTHORITY](-a-u-t-h-o-r-i-t-y.md) | `static val AUTHORITY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [CONTENT_URI](-c-o-n-t-e-n-t_-u-r-i.md) | `static val CONTENT_URI: Uri!` |
| [DOWNLOAD_HISTORY_URI](-d-o-w-n-l-o-a-d_-h-i-s-t-o-r-y_-u-r-i.md) | `static val DOWNLOAD_HISTORY_URI: Uri!` |
| [LOCATIONS_BY_SCHEDULED_STOP_URI](-l-o-c-a-t-i-o-n-s_-b-y_-s-c-h-e-d-u-l-e-d_-s-t-o-p_-u-r-i.md) | Only valid whilst bulkInserting. `static val LOCATIONS_BY_SCHEDULED_STOP_URI: Uri!` |
| [LOCATIONS_URI](-l-o-c-a-t-i-o-n-s_-u-r-i.md) | Supports insertion only - used for bulk transactions when inserting stops`static val LOCATIONS_URI: Uri!` |

### Functions

| Name | Summary |
|---|---|
| [bulkInsert](bulk-insert.md) | `open fun bulkInsert(uri: Uri!, values: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<ContentValues!>!): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [delete](delete.md) | `open fun delete(uri: Uri!, sel: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, selArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getType](get-type.md) | `open fun getType(uri: Uri!): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [insert](insert.md) | `open fun insert(uri: Uri!, values: ContentValues!): Uri!` |
| [onCreate](on-create.md) | `open fun onCreate(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [query](query.md) | `open fun query(uri: Uri!, proj: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!, sel: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, selArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!, sort: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): Cursor!` |
| [update](update.md) | `open fun update(uri: Uri!, values: ContentValues!, sel: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, selArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
