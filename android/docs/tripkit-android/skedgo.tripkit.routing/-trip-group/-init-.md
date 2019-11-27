[tripkit-android](../../index.md) / [skedgo.tripkit.routing](../index.md) / [TripGroup](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`TripGroup()`

Represents a list of ``[`Trip`](../-trip/index.md)s. A list of ``[`Trip`](../-trip/index.md)s comprises of a display trip (aka representative trip) and alternative trips. A display trip can be accessed via ``[`#getDisplayTrip()`](get-display-trip.md) while alternative trips can be retrieved via ``[`#getTrips()`](get-trips.md) minus ``[`#getDisplayTrip()`](get-display-trip.md). That's because ``[`#getTrips()`](get-trips.md) returns a list of ``[`Trip`](../-trip/index.md)s including alternative trips and display trip.

 Besides, a ``[`TripGroup`](index.md) also hold info related to ``[`Source`](../-source/index.md) via ``[`#getSources()`](get-sources.md).

