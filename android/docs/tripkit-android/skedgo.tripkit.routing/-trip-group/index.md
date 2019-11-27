[tripkit-android](../../index.md) / [skedgo.tripkit.routing](../index.md) / [TripGroup](./index.md)

# TripGroup

`open class TripGroup`

Represents a list of ``[`Trip`](../-trip/index.md)s. A list of ``[`Trip`](../-trip/index.md)s comprises of a display trip (aka representative trip) and alternative trips. A display trip can be accessed via ``[`#getDisplayTrip()`](get-display-trip.md) while alternative trips can be retrieved via ``[`#getTrips()`](get-trips.md) minus ``[`#getDisplayTrip()`](get-display-trip.md). That's because ``[`#getTrips()`](get-trips.md) returns a list of ``[`Trip`](../-trip/index.md)s including alternative trips and display trip.

 Besides, a ``[`TripGroup`](./index.md) also hold info related to ``[`Source`](../-source/index.md) via ``[`#getSources()`](get-sources.md).

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Represents a list of ``[`Trip`](../-trip/index.md)s. A list of ``[`Trip`](../-trip/index.md)s comprises of a display trip (aka representative trip) and alternative trips. A display trip can be accessed via ``[`#getDisplayTrip()`](get-display-trip.md) while alternative trips can be retrieved via ``[`#getTrips()`](get-trips.md) minus ``[`#getDisplayTrip()`](get-display-trip.md). That's because ``[`#getTrips()`](get-trips.md) returns a list of ``[`Trip`](../-trip/index.md)s including alternative trips and display trip. `TripGroup()` |

### Functions

| Name | Summary |
|---|---|
| [addAsDisplayTrip](add-as-display-trip.md) | A sample use case: Add a trip computed by waypoint API into trip list.`open fun addAsDisplayTrip(trip: `[`Trip`](../-trip/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [addTrip](add-trip.md) | `open fun addTrip(trip: `[`Trip`](../-trip/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [changeDisplayTrip](change-display-trip.md) | `open fun changeDisplayTrip(trip: `[`Trip`](../-trip/index.md)`): `[`TripGroup`](./index.md)`!` |
| [getDisplayTrip](get-display-trip.md) | `open fun getDisplayTrip(): `[`Trip`](../-trip/index.md)`?` |
| [getDisplayTripId](get-display-trip-id.md) | `open fun getDisplayTripId(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getFrequency](get-frequency.md) | `open fun getFrequency(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getSources](get-sources.md) | `open fun getSources(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Source`](../-source/index.md)`!>?` |
| [getTrips](get-trips.md) | `open fun getTrips(): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`Trip`](../-trip/index.md)`!>?` |
| [getVisibility](get-visibility.md) | `open fun getVisibility(): `[`GroupVisibility`](../-group-visibility/index.md)`!` |
| [setDisplayTripId](set-display-trip-id.md) | `open fun setDisplayTripId(displayTripId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setFrequency](set-frequency.md) | `open fun setFrequency(frequency: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSources](set-sources.md) | `open fun setSources(sources: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`Source`](../-source/index.md)`!>?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTrips](set-trips.md) | `open fun setTrips(trips: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`Trip`](../-trip/index.md)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setVisibility](set-visibility.md) | `open fun setVisibility(visibility: `[`GroupVisibility`](../-group-visibility/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [uuid](uuid.md) | `open fun uuid(uuid: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`open fun uuid(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |

### Extension Functions

| Name | Summary |
|---|---|
| [containsAnyMode](../contains-any-mode.md) | `fun `[`TripGroup`](./index.md)`.containsAnyMode(modeIds: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [containsMode](../contains-mode.md) | `fun `[`TripGroup`](./index.md)`.containsMode(modeId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getTrip](../get-trip.md) | `fun `[`TripGroup`](./index.md)`.getTrip(tripId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Trip`](../-trip/index.md)`?` |
