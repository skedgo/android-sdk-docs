[tripkit-android](../../index.md) / [com.skedgo.tripkit.a2brouting](../index.md) / [SelectBestDisplayTrip](./index.md)

# SelectBestDisplayTrip

`class SelectBestDisplayTrip : Function<`[`TripGroup`](../../com.skedgo.tripkit.routing/-trip-group/index.md)`!, `[`TripGroup`](../../com.skedgo.tripkit.routing/-trip-group/index.md)`!>`

Selects display trip which has lowest weighted score.

 If we leave after a certain query time, this helps pick the best display trip having start time that is not before the query time. Also, if we arrive by, it makes sure that display trip having end time which is after the query time will not be selected.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Selects display trip which has lowest weighted score. `SelectBestDisplayTrip()` |

### Functions

| Name | Summary |
|---|---|
| [apply](apply.md) | `fun apply(group: `[`TripGroup`](../../com.skedgo.tripkit.routing/-trip-group/index.md)`): `[`TripGroup`](../../com.skedgo.tripkit.routing/-trip-group/index.md) |
