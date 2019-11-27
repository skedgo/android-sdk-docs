[tripkit-android](../../index.md) / [com.skedgo.tripkit.data.database](../index.md) / [DbHelper](./index.md)

# DbHelper

`class DbHelper : SQLiteOpenHelper`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `DbHelper(context: Context, databaseName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, databaseMigrator: `[`DatabaseMigrator`](../-database-migrator/index.md)`)` |

### Functions

| Name | Summary |
|---|---|
| [onCreate](on-create.md) | `fun onCreate(database: SQLiteDatabase!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onUpgrade](on-upgrade.md) | `fun onUpgrade(database: SQLiteDatabase!, oldVersion: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, newVersion: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
