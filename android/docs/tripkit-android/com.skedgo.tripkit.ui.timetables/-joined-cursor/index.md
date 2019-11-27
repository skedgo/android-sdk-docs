[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables](../index.md) / [JoinedCursor](./index.md)

# JoinedCursor

`class JoinedCursor : AbstractCursor`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `JoinedCursor(leftCursor: Cursor, rightCursor: Cursor, leftJoinColumn: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, rightJoinColumn: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [leftCursor](left-cursor.md) | `val leftCursor: Cursor` |
| [leftJoinColumn](left-join-column.md) | `val leftJoinColumn: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [mapIdToRightCursorPosition](map-id-to-right-cursor-position.md) | `val mapIdToRightCursorPosition: `[`Map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-map/index.html)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [rightCursor](right-cursor.md) | `val rightCursor: Cursor` |
| [rightJoinColumn](right-join-column.md) | `val rightJoinColumn: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getColumnCount](get-column-count.md) | `fun getColumnCount(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getColumnNames](get-column-names.md) | `fun getColumnNames(): `[`Array`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-array/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [getCount](get-count.md) | `fun getCount(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDouble](get-double.md) | `fun getDouble(column: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getFloat](get-float.md) | `fun getFloat(column: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getInt](get-int.md) | `fun getInt(column: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getLong](get-long.md) | `fun getLong(column: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getNotificationUri](get-notification-uri.md) | `fun getNotificationUri(): Uri` |
| [getShort](get-short.md) | `fun getShort(column: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Short`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-short/index.html) |
| [getString](get-string.md) | `fun getString(column: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getType](get-type.md) | `fun getType(column: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [isNull](is-null.md) | `fun isNull(column: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onMove](on-move.md) | `fun onMove(oldPosition: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, newPosition: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [registerContentObserver](register-content-observer.md) | `fun registerContentObserver(observer: ContentObserver): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [registerDataSetObserver](register-data-set-observer.md) | `fun registerDataSetObserver(observer: DataSetObserver?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setNotificationUri](set-notification-uri.md) | `fun setNotificationUri(cr: ContentResolver?, notifyUri: Uri?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [unregisterContentObserver](unregister-content-observer.md) | `fun unregisterContentObserver(observer: ContentObserver?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [unregisterDataSetObserver](unregister-data-set-observer.md) | `fun unregisterDataSetObserver(observer: DataSetObserver?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
