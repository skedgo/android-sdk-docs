[tripkit-android](../../index.md) / [skedgo.tripkit.routing](../index.md) / [TripGroup](index.md) / [changeDisplayTrip](./change-display-trip.md)

# changeDisplayTrip

`open fun changeDisplayTrip(@NonNull trip: `[`Trip`](../-trip/index.md)`): `[`TripGroup`](index.md)`!`

### Parameters

`trip` - [Trip](../-trip/index.md): This trip must belong to group's trips. Otherwise, ``[`IllegalStateException`](https://docs.oracle.com/javase/7/docs/api/java/lang/IllegalStateException.html) will be thrown.

### Exceptions

`IllegalStateException` - if the trip doesn't belong to the group.

**Return**
[TripGroup](index.md)!: A TripGroup having new display trip.

