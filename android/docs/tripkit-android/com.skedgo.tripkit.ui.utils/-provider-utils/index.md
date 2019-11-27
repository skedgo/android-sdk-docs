[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.utils](../index.md) / [ProviderUtils](./index.md)

# ProviderUtils

`open class ProviderUtils`

**Author**
Daniel Grech

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ProviderUtils()` |

### Functions

| Name | Summary |
|---|---|
| [doBulkInsert](do-bulk-insert.md) | Insert multiple rows`open static fun doBulkInsert(c: Context!, providerUri: Uri!, valuesArray: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<ContentValues!>!): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [doDelete](do-delete.md) | `open static fun doDelete(c: Context!, providerUri: Uri!, where: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [doInsert](do-insert.md) | `open static fun doInsert(c: Context!, providerUri: Uri!, values: ContentValues!): Uri!` |
| [doUpdate](do-update.md) | `open static fun doUpdate(c: Context!, providerUri: Uri!, values: ContentValues!, sel: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, selArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [upsert](upsert.md) | `open static fun upsert(db: SQLiteDatabase!, table: DatabaseTable!, values: ContentValues!, fieldToMatch: DatabaseField?): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)<br>`open static fun upsert(db: SQLiteDatabase!, table: DatabaseTable!, values: ContentValues!, fieldsToMatch: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<DatabaseField!>?): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
