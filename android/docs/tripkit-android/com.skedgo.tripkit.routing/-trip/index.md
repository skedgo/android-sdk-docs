[tripkit-android](../../index.md) / [com.skedgo.tripkit.routing](../index.md) / [Trip](./index.md)

# Trip

`open class Trip : `[`ITimeRange`](../../com.skedgo.tripkit.common.model/-i-time-range/index.md)

A ``[`Trip`](./index.md) will mainly hold a list of ``[`TripSegment`](../-trip-segment/index.md)s which denotes how to go from ``[`Trip#getFrom()`](get-from.md) to ``[`Trip#getTo()`](get-to.md).

 Main use-cases: - Trip's segments: ``[`Trip#getSegments()`](get-segments.md). - Trip's start time: ``[`TripExtensionsKt#getStartDateTime(Trip)`](../start-date-time.md). - Trip's end time: ``[`TripExtensionsKt#getEndDateTime(Trip)`](../end-date-time.md)}. - Trip's costs: ``[`#getCaloriesCost()`](get-calories-cost.md), ``[`#getMoneyCost()`](get-money-cost.md), ``[`#getCarbonCost()`](get-carbon-cost.md).

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Trip()` |

### Properties

| Name | Summary |
|---|---|
| [rawSegmentList](raw-segment-list.md) | This will be transformed into a list of ``[`TripSegment`](../-trip-segment/index.md).`var rawSegmentList: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<JsonObject!>!` |
| [UNKNOWN_COST](-u-n-k-n-o-w-n_-c-o-s-t.md) | `static val UNKNOWN_COST: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |

### Functions

| Name | Summary |
|---|---|
| [durationInSeconds](duration-in-seconds.md) | `open fun durationInSeconds(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getAvailability](get-availability.md) | Indicates availability of the trip, e.g., if it's too late to book a trip for the requested departure time, or if a scheduled service has been cancelled.`open fun getAvailability(): `[`Availability`](../-availability/index.md)`?` |
| [getCaloriesCost](get-calories-cost.md) | `open fun getCaloriesCost(): `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getCarbonCost](get-carbon-cost.md) | `open fun getCarbonCost(): `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getCurrencySymbol](get-currency-symbol.md) | `open fun getCurrencySymbol(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getDisplayCalories](get-display-calories.md) | `open fun getDisplayCalories(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getDisplayCarbonCost](get-display-carbon-cost.md) | `open fun getDisplayCarbonCost(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getDisplayCost](get-display-cost.md) | `open fun getDisplayCost(localizedFreeText: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getEndTimeInSecs](get-end-time-in-secs.md) | Use ``[`TripExtensionsKt#getEndDateTime(Trip)`](../end-date-time.md) instead.`open fun getEndTimeInSecs(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getFrom](get-from.md) | `open fun getFrom(): `[`Location`](../../com.skedgo.tripkit.common.model/-location/index.md)`!` |
| [getGroup](get-group.md) | `open fun getGroup(): `[`TripGroup`](../-trip-group/index.md)`!` |
| [getHassleCost](get-hassle-cost.md) | `open fun getHassleCost(): `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getId](get-id.md) | `open fun getId(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getMoneyCost](get-money-cost.md) | `open fun getMoneyCost(): `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getPlannedURL](get-planned-u-r-l.md) | `open fun getPlannedURL(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getProgressURL](get-progress-u-r-l.md) | `open fun getProgressURL(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getSaveURL](get-save-u-r-l.md) | `open fun getSaveURL(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getSegments](get-segments.md) | `open fun getSegments(): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`TripSegment`](../-trip-segment/index.md)`!>!` |
| [getStartTimeInSecs](get-start-time-in-secs.md) | Use ``[`TripExtensionsKt#getStartDateTime(Trip)`](../start-date-time.md) instead.`open fun getStartTimeInSecs(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getTemporaryURL](get-temporary-u-r-l.md) | `open fun getTemporaryURL(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getTimeCost](get-time-cost.md) | `open fun getTimeCost(): `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getTo](get-to.md) | `open fun getTo(): `[`Location`](../../com.skedgo.tripkit.common.model/-location/index.md)`!` |
| [getUpdateURL](get-update-u-r-l.md) | `open fun getUpdateURL(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getWeightedScore](get-weighted-score.md) | `open fun getWeightedScore(): `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [hasAnyExpensiveTransport](has-any-expensive-transport.md) | Check if this trip has shuffle, taxi or shared vehicle.`open fun hasAnyExpensiveTransport(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasAnyPublicTransport](has-any-public-transport.md) | `open fun hasAnyPublicTransport(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasQuickBooking](has-quick-booking.md) | `open fun hasQuickBooking(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hasTransportMode](has-transport-mode.md) | `open fun hasTransportMode(vararg modes: `[`VehicleMode`](../-vehicle-mode/index.md)`!): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isDepartureTimeFixed](is-departure-time-fixed.md) | Adrian: "duration (arrive)" should be used for transport where the departure time isn't fixed, such as driving trips not involving public transport, or public transport trips that use only frequency-based trips.`open fun isDepartureTimeFixed(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isFavourite](is-favourite.md) | `open fun isFavourite(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>`open fun isFavourite(isFavourite: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [isMixedModal](is-mixed-modal.md) | `open fun isMixedModal(ignoreWalking: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [queryIsLeaveAfter](query-is-leave-after.md) | `open fun queryIsLeaveAfter(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setCaloriesCost](set-calories-cost.md) | `open fun setCaloriesCost(caloriesCost: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setCarbonCost](set-carbon-cost.md) | `open fun setCarbonCost(carbonCost: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setEndTimeInSecs](set-end-time-in-secs.md) | NOTE: You should only use this setter for testing purpose.`open fun setEndTimeInSecs(endTimeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setGroup](set-group.md) | `open fun setGroup(group: `[`TripGroup`](../-trip-group/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setHassleCost](set-hassle-cost.md) | `open fun setHassleCost(hassleCost: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setId](set-id.md) | `open fun setId(id: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setMoneyCost](set-money-cost.md) | `open fun setMoneyCost(moneyCost: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSaveURL](set-save-u-r-l.md) | `open fun setSaveURL(saveURL: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSegments](set-segments.md) | `open fun setSegments(segments: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`TripSegment`](../-trip-segment/index.md)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setStartTimeInSecs](set-start-time-in-secs.md) | NOTE: You should only use this setter for testing purpose.`open fun setStartTimeInSecs(startTimeInSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTemporaryURL](set-temporary-u-r-l.md) | `open fun setTemporaryURL(temporaryURL: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setUpdateURL](set-update-u-r-l.md) | `open fun setUpdateURL(updateURL: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setWeightedScore](set-weighted-score.md) | `open fun setWeightedScore(weightedScore: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [uuid](uuid.md) | `open fun uuid(uuid: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`open fun uuid(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |

### Extension Properties

| Name | Summary |
|---|---|
| [endDateTime](../end-date-time.md) | Get an end date-time with time-zone.`val `[`Trip`](./index.md)`.endDateTime: DateTime` |
| [startDateTime](../start-date-time.md) | Gets a start date-time with time-zone.`val `[`Trip`](./index.md)`.startDateTime: DateTime` |

### Extension Functions

| Name | Summary |
|---|---|
| [constructPlainText](../construct-plain-text.md) | `fun `[`Trip`](./index.md)`.constructPlainText(context: Context): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getModeIds](../get-mode-ids.md) | `fun `[`Trip`](./index.md)`.getModeIds(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [getSummarySegments](../get-summary-segments.md) | Gets a list of [TripSegment](../-trip-segment/index.md)s visible on the summary area of a [Trip](./index.md).`fun `[`Trip`](./index.md)`.getSummarySegments(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`TripSegment`](../-trip-segment/index.md)`>` |
| [getTripSegment](../get-trip-segment.md) | `fun `[`Trip`](./index.md)`.getTripSegment(segmentId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`TripSegment`](../-trip-segment/index.md)`?` |
| [hasWalkOnly](../has-walk-only.md) | `fun `[`Trip`](./index.md)`.hasWalkOnly(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
