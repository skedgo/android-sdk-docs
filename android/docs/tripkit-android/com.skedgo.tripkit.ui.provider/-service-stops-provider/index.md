[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.provider](../index.md) / [ServiceStopsProvider](./index.md)

# ServiceStopsProvider

`class ServiceStopsProvider : ContentProvider`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServiceStopsProvider()` |

### Functions

| Name | Summary |
|---|---|
| [bulkInsert](bulk-insert.md) | `fun bulkInsert(uri: Uri, values: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<ContentValues>): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [delete](delete.md) | `fun delete(uri: Uri, sel: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, selArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getType](get-type.md) | `fun getType(uri: Uri): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [insert](insert.md) | `fun insert(uri: Uri, values: ContentValues?): Uri?` |
| [onCreate](on-create.md) | `fun onCreate(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [query](query.md) | `fun query(uri: Uri, proj: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?, sel: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, selArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?, sort: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): Cursor` |
| [update](update.md) | `fun update(uri: Uri, values: ContentValues?, sel: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?, selArgs: `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Companion Object Properties

| Name | Summary |
|---|---|
| [AUTHORITY](-a-u-t-h-o-r-i-t-y.md) | `val AUTHORITY: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [LOCATIONS_URI](-l-o-c-a-t-i-o-n-s_-u-r-i.md) | `val LOCATIONS_URI: Uri!` |
| [SHAPES_URI](-s-h-a-p-e-s_-u-r-i.md) | `val SHAPES_URI: Uri!` |
| [STOPS_BY_SERVICE_URI](-s-t-o-p-s_-b-y_-s-e-r-v-i-c-e_-u-r-i.md) | `val STOPS_BY_SERVICE_URI: Uri!` |
| [STOPS_URI](-s-t-o-p-s_-u-r-i.md) | Supports insertion only - used for batch transactions when inserting stops`val STOPS_URI: Uri!` |
