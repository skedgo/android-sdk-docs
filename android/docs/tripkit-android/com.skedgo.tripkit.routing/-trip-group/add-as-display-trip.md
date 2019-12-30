[tripkit-android](../../index.md) / [com.skedgo.tripkit.routing](../index.md) / [TripGroup](index.md) / [addAsDisplayTrip](./add-as-display-trip.md)

# addAsDisplayTrip

`open fun addAsDisplayTrip(@NonNull trip: `[`Trip`](../-trip/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

A sample use case: Add a trip computed by waypoint API into trip list.

### Parameters

`trip` - [Trip](../-trip/index.md): This trip must not belong to group's trips. Otherwise, ``[`IllegalStateException`](https://docs.oracle.com/javase/7/docs/api/java/lang/IllegalStateException.html) will be thrown.

### Exceptions

`IllegalStateException` - if the trip already belongs to the group. To change display trip, should invoke ``[`TripGroup#changeDisplayTrip(Trip)`](change-display-trip.md) instead.