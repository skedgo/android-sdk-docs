[tripkit-android](../../index.md) / [skedgo.tripkit.routing](../index.md) / [TripSegment](./index.md)

# TripSegment

`open class TripSegment : `[`IRealTimeElement`](../../com.skedgo.android.common.agenda/-i-real-time-element/index.md)`, `[`ITimeRange`](../../com.skedgo.android.common.model/-i-time-range/index.md)

To go from A to B, sometimes we have to travel X, Y, Z locations between A and B. That means, we travel A to X, then X to Y, then Y to Z, then Z to B which is the destination. To show how to travel from A to X, we use ``[`TripSegment`](./index.md). So, in this case, a trip from A to B comprises 6 segments: - A segment whose type is ``[`SegmentType#DEPARTURE`](../-segment-type/-d-e-p-a-r-t-u-r-e.md). - A segment from A to X. - A segment from X to Y. - A segment from Y to Z. - A segment from Z to B. - A segment whose type is ``[`SegmentType#ARRIVAL`](../-segment-type/-a-r-r-i-v-a-l.md).

 Note that, to avoid ``[`TransactionTooLargeException`](#), it's discouraged to pass any instance of ``[`Query`](../../com.skedgo.android.common.model/-query/index.md) to ``[`Intent`](#) or ``[`Bundle`](#). The ``[`Parcelable`](#) is subject to deletion at anytime.

**See Also**
&lt;a href="http://skedgo.github.io/tripgo-api/site/faq/#trips-groups-frequencies-and-templates"&gt;Trips, groups, frequencies and templates&lt;/a&gt;

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | To go from A to B, sometimes we have to travel X, Y, Z locations between A and B. That means, we travel A to X, then X to Y, then Y to Z, then Z to B which is the destination. To show how to travel from A to X, we use ``[`TripSegment`](./index.md). So, in this case, a trip from A to B comprises 6 segments: - A segment whose type is ``[`SegmentType#DEPARTURE`](../-segment-type/-d-e-p-a-r-t-u-r-e.md). - A segment from A to X. - A segment from X to Y. - A segment from Y to Z. - A segment from Z to B. - A segment whose type is ``[`SegmentType#ARRIVAL`](../-segment-type/-a-r-r-i-v-a-l.md). `TripSegment()` |

### Functions

| Name | Summary |
|---|---|
| [convertStopCountToText](convert-stop-count-to-text.md) | FIXME: Should replace this with Quantity Strings. See http://developer.android.com/intl/vi/guide/topics/resources/string-resource.html#Plurals.`open static fun convertStopCountToText(stopCount: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getAction](get-action.md) | `open fun getAction(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getAlertHashCodes](get-alert-hash-codes.md) | `open fun getAlertHashCodes(): `[`LongArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long-array/index.html)`!` |
| [getAlerts](get-alerts.md) | `open fun getAlerts(): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`!>?` |
| [getBooking](get-booking.md) | `open fun getBooking(): `[`Booking`](../../com.skedgo.android.common.model/-booking/index.md)`!` |
| [getCycleFriendliness](get-cycle-friendliness.md) | `open fun getCycleFriendliness(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDarkVehicleIcon](get-dark-vehicle-icon.md) | `open fun getDarkVehicleIcon(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDirection](get-direction.md) | `open fun getDirection(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getDisplayNotes](get-display-notes.md) | As of now, used only for unscheduled segments. If we want to show notes on views, use it instead of `getNotes`. Some essential templates will be resolved before being presented by the views.`open fun getDisplayNotes(resources: Resources!): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getDurationWithoutTraffic](get-duration-without-traffic.md) | `open fun getDurationWithoutTraffic(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getEndStopCode](get-end-stop-code.md) | `open fun getEndStopCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getFrequency](get-frequency.md) | `open fun getFrequency(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getFrom](get-from.md) | `open fun getFrom(): `[`Location`](../../com.skedgo.android.common.model/-location/index.md)`!` |
| [getId](get-id.md) | `open fun getId(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getLightTransportIcon](get-light-transport-icon.md) | `open fun getLightTransportIcon(resources: Resources): Drawable!` |
| [getLocalCost](get-local-cost.md) | `open fun getLocalCost(): `[`LocalCost`](../-local-cost/index.md)`?` |
| [getMetres](get-metres.md) | `open fun getMetres(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMetresSafe](get-metres-safe.md) | `open fun getMetresSafe(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getMetresUnsafe](get-metres-unsafe.md) | `open fun getMetresUnsafe(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getModeInfo](get-mode-info.md) | `open fun getModeInfo(): `[`ModeInfo`](../-mode-info/index.md)`?` |
| [getNotes](get-notes.md) | NOTE: For unscheduled segments, if we want to show notes on views, don't call this. Call `getDisplayNotes` instead.`open fun getNotes(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getOperator](get-operator.md) | `open fun getOperator(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getPairIdentifier](get-pair-identifier.md) | `open fun getPairIdentifier(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getPlatform](get-platform.md) | `open fun getPlatform(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getRealTimeStatusText](get-real-time-status-text.md) | `open fun getRealTimeStatusText(resources: Resources!): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getRealTimeVehicle](get-real-time-vehicle.md) | `open fun getRealTimeVehicle(): `[`RealTimeVehicle`](../-real-time-vehicle/index.md)`!` |
| [getServiceColor](get-service-color.md) | `open fun getServiceColor(): `[`ServiceColor`](../-service-color/index.md)`?` |
| [getServiceDirection](get-service-direction.md) | `open fun getServiceDirection(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getServiceName](get-service-name.md) | `open fun getServiceName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getServiceNumber](get-service-number.md) | `open fun getServiceNumber(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getServiceOperator](get-service-operator.md) | `open fun getServiceOperator(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getServiceTripId](get-service-trip-id.md) | `open fun getServiceTripId(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getShapes](get-shapes.md) | `open fun getShapes(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Shape`](../-shape/index.md)`!>?` |
| [getSingleLocation](get-single-location.md) | `open fun getSingleLocation(): `[`Location`](../../com.skedgo.android.common.model/-location/index.md)`!` |
| [getStartStopCode](get-start-stop-code.md) | `open fun getStartStopCode(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getStopCount](get-stop-count.md) | `open fun getStopCount(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getStreets](get-streets.md) | `open fun getStreets(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Street`](../../com.skedgo.android.common.model/-street/index.md)`!>!` |
| [getTemplateHashCode](get-template-hash-code.md) | `open fun getTemplateHashCode(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getTerms](get-terms.md) | `open fun getTerms(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getTimeZone](get-time-zone.md) | `open fun getTimeZone(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getTo](get-to.md) | `open fun getTo(): `[`Location`](../../com.skedgo.android.common.model/-location/index.md)`!` |
| [getTransportModeId](get-transport-mode-id.md) | Segments having type as ``[`SegmentType#DEPARTURE`](../-segment-type/-d-e-p-a-r-t-u-r-e.md), ``[`SegmentType#ARRIVAL`](../-segment-type/-a-r-r-i-v-a-l.md), and ``[`SegmentType#STATIONARY`](../-segment-type/-s-t-a-t-i-o-n-a-r-y.md) will have this property as null. `open fun getTransportModeId(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getTrip](get-trip.md) | `open fun getTrip(): `[`Trip`](../-trip/index.md)`!` |
| [getTurnByTurn](get-turn-by-turn.md) | `open fun getTurnByTurn(): `[`TurnByTurn`](../-turn-by-turn/index.md)`?` |
| [getType](get-type.md) | `open fun getType(): `[`SegmentType`](../-segment-type/index.md)`?` |
| [getVisibility](get-visibility.md) | `open fun getVisibility(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getWheelchairAccessible](get-wheelchair-accessible.md) | `open fun getWheelchairAccessible(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getWheelchairFriendliness](get-wheelchair-friendliness.md) | `open fun getWheelchairFriendliness(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [hasTimeTable](has-time-table.md) | `open fun hasTimeTable(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isContinuation](is-continuation.md) | `open fun isContinuation(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isCycling](is-cycling.md) | `open fun isCycling(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isFrequencyBased](is-frequency-based.md) | `open fun isFrequencyBased(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>`open fun isFrequencyBased(isFrequencyBased: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [isPlane](is-plane.md) | `open fun isPlane(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isRealTime](is-real-time.md) | `open fun isRealTime(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isStationary](is-stationary.md) | `open fun isStationary(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isVisibleInContext](is-visible-in-context.md) | `open fun isVisibleInContext(contextVisibility: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isWalking](is-walking.md) | `open fun isWalking(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isWheelchair](is-wheelchair.md) | `open fun isWheelchair(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [lineColor](line-color.md) | `open fun lineColor(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [setAction](set-action.md) | `open fun setAction(action: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setAlertHashCodes](set-alert-hash-codes.md) | `open fun setAlertHashCodes(alertHashCodes: `[`LongArray`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long-array/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setAlerts](set-alerts.md) | `open fun setAlerts(alerts: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setBooking](set-booking.md) | `open fun setBooking(booking: `[`Booking`](../../com.skedgo.android.common.model/-booking/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setContinuation](set-continuation.md) | `open fun setContinuation(isContinuation: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setDirection](set-direction.md) | `open fun setDirection(direction: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setDurationWithoutTraffic](set-duration-without-traffic.md) | `open fun setDurationWithoutTraffic(durationWithoutTraffic: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setEndStopCode](set-end-stop-code.md) | `open fun setEndStopCode(endStopCode: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setEndTimeInSecs](set-end-time-in-secs.md) | NOTE: You should only use this setter for testing purpose.`open fun setEndTimeInSecs(newEndTimeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setFrequency](set-frequency.md) | `open fun setFrequency(frequency: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setFrom](set-from.md) | `open fun setFrom(from: `[`Location`](../../com.skedgo.android.common.model/-location/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setId](set-id.md) | `open fun setId(id: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setMetres](set-metres.md) | `open fun setMetres(metres: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setMetresSafe](set-metres-safe.md) | `open fun setMetresSafe(metresSafe: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setMetresUnsafe](set-metres-unsafe.md) | `open fun setMetresUnsafe(metresUnsafe: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setModeInfo](set-mode-info.md) | `open fun setModeInfo(modeInfo: `[`ModeInfo`](../-mode-info/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setNotes](set-notes.md) | `open fun setNotes(notes: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setPlatform](set-platform.md) | `open fun setPlatform(platform: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRealTime](set-real-time.md) | `open fun setRealTime(isRealTime: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRealTimeVehicle](set-real-time-vehicle.md) | `open fun setRealTimeVehicle(realTimeVehicle: `[`RealTimeVehicle`](../-real-time-vehicle/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceColor](set-service-color.md) | `open fun setServiceColor(serviceColor: `[`ServiceColor`](../-service-color/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceDirection](set-service-direction.md) | `open fun setServiceDirection(serviceDirection: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceName](set-service-name.md) | `open fun setServiceName(serviceName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceNumber](set-service-number.md) | `open fun setServiceNumber(serviceNumber: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceOperator](set-service-operator.md) | `open fun setServiceOperator(serviceOperator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setServiceTripId](set-service-trip-id.md) | `open fun setServiceTripId(serviceTripId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setShapes](set-shapes.md) | `open fun setShapes(shapes: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`Shape`](../-shape/index.md)`!>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSingleLocation](set-single-location.md) | `open fun setSingleLocation(singleLocation: `[`Location`](../../com.skedgo.android.common.model/-location/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStartStopCode](set-start-stop-code.md) | `open fun setStartStopCode(startStopCode: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStartTimeInSecs](set-start-time-in-secs.md) | NOTE: You should only use this setter for testing purpose.`open fun setStartTimeInSecs(newStartTimeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStopCount](set-stop-count.md) | `open fun setStopCount(stopCount: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStreets](set-streets.md) | `open fun setStreets(streets: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`Street`](../../com.skedgo.android.common.model/-street/index.md)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTemplateHashCode](set-template-hash-code.md) | `open fun setTemplateHashCode(templateHashCode: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTerms](set-terms.md) | `open fun setTerms(terms: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTo](set-to.md) | `open fun setTo(to: `[`Location`](../../com.skedgo.android.common.model/-location/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTransportModeId](set-transport-mode-id.md) | `open fun setTransportModeId(transportModeId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTrip](set-trip.md) | `open fun setTrip(trip: `[`Trip`](../-trip/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setType](set-type.md) | `open fun setType(type: `[`SegmentType`](../-segment-type/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setVisibility](set-visibility.md) | `open fun setVisibility(visibility: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setWheelchairAccessible](set-wheelchair-accessible.md) | `open fun setWheelchairAccessible(wheelchairAccessible: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Properties

| Name | Summary |
|---|---|
| [actionAlert](../action-alert.md) | `val `[`TripSegment`](./index.md)`.actionAlert: `[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`?` |
| [endDateTime](../end-date-time.md) | Get an end date-time with time-zone.`val `[`TripSegment`](./index.md)`.endDateTime: DateTime` |
| [noActionAlerts](../no-action-alerts.md) | `val `[`TripSegment`](./index.md)`.noActionAlerts: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`RealtimeAlert`](../../com.skedgo.android.common.model/-realtime-alert/index.md)`!>?` |
| [startDateTime](../start-date-time.md) | Gets a start date-time with time-zone.`val `[`TripSegment`](./index.md)`.startDateTime: DateTime` |
