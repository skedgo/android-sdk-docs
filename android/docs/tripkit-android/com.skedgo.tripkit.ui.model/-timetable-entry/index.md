[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.model](../index.md) / [TimetableEntry](./index.md)

# TimetableEntry

`open class TimetableEntry : Parcelable, `[`IRealTimeElement`](../../com.skedgo.tripkit.common.agenda/-i-real-time-element/index.md)`, `[`ITimeRange`](../../com.skedgo.tripkit.common.model/-i-time-range/index.md)`, `[`WheelchairAccessible`](../../com.skedgo.tripkit.common.model/-wheelchair-accessible/index.md)

(Aka Service)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TimetableEntry()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`TimetableEntry`](./index.md)`!>!` |
| [endStop](end-stop.md) | For A2B-timetable-related stuff.`var endStop: `[`ScheduledStop`](../../com.skedgo.tripkit.common.model/-scheduled-stop/index.md)`!` |
| [pairIdentifier](pair-identifier.md) | For A2B-timetable-related stuff.`var pairIdentifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [startStop](start-stop.md) | For A2B-timetable-related stuff.`var startStop: `[`ScheduledStop`](../../com.skedgo.tripkit.common.model/-scheduled-stop/index.md)`!` |
| [stops](stops.md) | `val stops: Var<`[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`StopInfo`](../-stop-info/index.md)`!>!>!` |
| [wheelchairAccessible](wheelchair-accessible.md) | `open val wheelchairAccessible: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?` |

### Functions

| Name | Summary |
|---|---|
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getAlertHashCodes](get-alert-hash-codes.md) | `open fun getAlertHashCodes(): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`!>?` |
| [getAlerts](get-alerts.md) | `open fun getAlerts(): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`RealtimeAlert`](../../com.skedgo.tripkit.common.model/-realtime-alert/index.md)`!>!` |
| [getEndStopCode](get-end-stop-code.md) | `open fun getEndStopCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getEndTimeInSecs](get-end-time-in-secs.md) | `open fun getEndTimeInSecs(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getFrequency](get-frequency.md) | `open fun getFrequency(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getId](get-id.md) | `open fun getId(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getModeInfo](get-mode-info.md) | `open fun getModeInfo(): `[`ModeInfo`](../../com.skedgo.tripkit.routing/-mode-info/index.md)`?` |
| [getOperator](get-operator.md) | `open fun getOperator(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getRealTimeArrival](get-real-time-arrival.md) | `open fun getRealTimeArrival(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getRealTimeDeparture](get-real-time-departure.md) | `open fun getRealTimeDeparture(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getRealTimeStatus](get-real-time-status.md) | `open fun getRealTimeStatus(): `[`RealTimeStatus`](../../com.skedgo.tripkit.common.model/-real-time-status/index.md)`!` |
| [getRealtimeVehicle](get-realtime-vehicle.md) | `open fun getRealtimeVehicle(): `[`RealTimeVehicle`](../../com.skedgo.tripkit.routing/-real-time-vehicle/index.md)`!` |
| [getSearchString](get-search-string.md) | `open fun getSearchString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getServiceColor](get-service-color.md) | `open fun getServiceColor(): `[`ServiceColor`](../../com.skedgo.tripkit.routing/-service-color/index.md)`!` |
| [getServiceDirection](get-service-direction.md) | `open fun getServiceDirection(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getServiceName](get-service-name.md) | `open fun getServiceName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getServiceNumber](get-service-number.md) | `open fun getServiceNumber(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getServiceTime](get-service-time.md) | In secs.`open fun getServiceTime(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getServiceTripId](get-service-trip-id.md) | `open fun getServiceTripId(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getStartStopCode](get-start-stop-code.md) | `open fun getStartStopCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getStartStopShortName](get-start-stop-short-name.md) | `open fun getStartStopShortName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getStartTimeInSecs](get-start-time-in-secs.md) | `open fun getStartTimeInSecs(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getStopCode](get-stop-code.md) | `open fun getStopCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [hasAlerts](has-alerts.md) | `open fun hasAlerts(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isBefore](is-before.md) | For example, in order to determine a past service trip.`open fun isBefore(pointSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isFavourite](is-favourite.md) | `open fun isFavourite(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>`open fun isFavourite(isFavourite: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [isFrequencyBased](is-frequency-based.md) | `open fun isFrequencyBased(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setAlertHashCodes](set-alert-hash-codes.md) | `open fun setAlertHashCodes(alertHashCodes: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`!>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setAlerts](set-alerts.md) | `open fun setAlerts(alerts: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`RealtimeAlert`](../../com.skedgo.tripkit.common.model/-realtime-alert/index.md)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setEndStopCode](set-end-stop-code.md) | `open fun setEndStopCode(endStopCode: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setEndTimeInSecs](set-end-time-in-secs.md) | `open fun setEndTimeInSecs(endTimeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setFrequency](set-frequency.md) | `open fun setFrequency(freq: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setId](set-id.md) | `open fun setId(id: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setModeInfo](set-mode-info.md) | `open fun setModeInfo(modeInfo: `[`ModeInfo`](../../com.skedgo.tripkit.routing/-mode-info/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setOperator](set-operator.md) | `open fun setOperator(operator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRealTimeArrival](set-real-time-arrival.md) | `open fun setRealTimeArrival(realTimeArrival: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRealTimeDeparture](set-real-time-departure.md) | `open fun setRealTimeDeparture(realTimeDeparture: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRealTimeStatus](set-real-time-status.md) | `open fun setRealTimeStatus(realTimeStatus: `[`RealTimeStatus`](../../com.skedgo.tripkit.common.model/-real-time-status/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRealtimeVehicle](set-realtime-vehicle.md) | `open fun setRealtimeVehicle(realtimeVehicle: `[`RealTimeVehicle`](../../com.skedgo.tripkit.routing/-real-time-vehicle/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSearchString](set-search-string.md) | `open fun setSearchString(searchString: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceColor](set-service-color.md) | `open fun setServiceColor(serviceColor: `[`ServiceColor`](../../com.skedgo.tripkit.routing/-service-color/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceDirection](set-service-direction.md) | `open fun setServiceDirection(serviceDirection: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceName](set-service-name.md) | `open fun setServiceName(serviceName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceNumber](set-service-number.md) | `open fun setServiceNumber(serviceNumber: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceTime](set-service-time.md) | `open fun setServiceTime(serviceTime: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceTripId](set-service-trip-id.md) | `open fun setServiceTripId(serviceTripId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStartStopCode](set-start-stop-code.md) | `open fun setStartStopCode(startStopCode: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStartStopShortName](set-start-stop-short-name.md) | `open fun setStartStopShortName(startStopShortName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStartTimeInSecs](set-start-time-in-secs.md) | `open fun setStartTimeInSecs(startTimeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStopCode](set-stop-code.md) | `open fun setStopCode(stopCode: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setWheelchairAccessible](set-wheelchair-accessible.md) | `open fun setWheelchairAccessible(wheelchairAccessible: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toString](to-string.md) | For debug purpose only.`open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(out: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [getTimeLeftToDepartInterval](../../com.skedgo.tripkit.ui.timetables/get-time-left-to-depart-interval.md) | `fun `[`TimetableEntry`](./index.md)`.getTimeLeftToDepartInterval(period: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`, timeUnit: `[`TimeUnit`](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/TimeUnit.html)`): Observable<`[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`>` |
