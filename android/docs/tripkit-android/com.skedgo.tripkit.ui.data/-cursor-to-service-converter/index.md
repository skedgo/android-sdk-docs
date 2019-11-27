[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.data](../index.md) / [CursorToServiceConverter](./index.md)

# CursorToServiceConverter

`open class CursorToServiceConverter : `[`CursorToEntityConverter`](../-cursor-to-entity-converter.md)`<`[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`!>`

### Types

| Name | Summary |
|---|---|
| [ServiceColumnIndices](-service-column-indices/index.md) | NOTE: Don't hard code column indices`open class ServiceColumnIndices` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `CursorToServiceConverter(gson: Gson)` |

### Functions

| Name | Summary |
|---|---|
| [apply](apply.md) | `open fun apply(cursor: Cursor): `[`TimetableEntry`](../../com.skedgo.tripkit.ui.model/-timetable-entry/index.md)`!` |
| [getEndStopCode](get-end-stop-code.md) | `open fun getEndStopCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getEndTimeInSecs](get-end-time-in-secs.md) | `open fun getEndTimeInSecs(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getFrequency](get-frequency.md) | `open fun getFrequency(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getId](get-id.md) | `open fun getId(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getMode](get-mode.md) | `open fun getMode(): `[`VehicleMode`](../../skedgo.tripkit.routing/-vehicle-mode/index.md)`!` |
| [getPairIdentifier](get-pair-identifier.md) | `open fun getPairIdentifier(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getRealTimeStatus](get-real-time-status.md) | `open fun getRealTimeStatus(): `[`RealTimeStatus`](../../com.skedgo.android.common.model/-real-time-status/index.md)`!` |
| [getSearchString](get-search-string.md) | `open fun getSearchString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getServiceColorBlue](get-service-color-blue.md) | `open fun getServiceColorBlue(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getServiceColorGreen](get-service-color-green.md) | `open fun getServiceColorGreen(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getServiceColorRed](get-service-color-red.md) | `open fun getServiceColorRed(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getServiceName](get-service-name.md) | `open fun getServiceName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getServiceNumber](get-service-number.md) | `open fun getServiceNumber(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getServiceOperator](get-service-operator.md) | `open fun getServiceOperator(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getServiceTime](get-service-time.md) | `open fun getServiceTime(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getServiceTripId](get-service-trip-id.md) | `open fun getServiceTripId(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getStartStopShortName](get-start-stop-short-name.md) | `open fun getStartStopShortName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getStartTimeInSecs](get-start-time-in-secs.md) | `open fun getStartTimeInSecs(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getStopCode](get-stop-code.md) | `open fun getStopCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getWheelchairAccessible](get-wheelchair-accessible.md) | `open fun getWheelchairAccessible(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`!` |
| [isFavourite](is-favourite.md) | `open fun isFavourite(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setCursor](set-cursor.md) | `open fun setCursor(cursor: Cursor): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
