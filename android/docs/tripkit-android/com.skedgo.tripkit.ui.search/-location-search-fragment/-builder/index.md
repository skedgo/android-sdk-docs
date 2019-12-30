[tripkit-android](../../../index.md) / [com.skedgo.tripkit.ui.search](../../index.md) / [LocationSearchFragment](../index.md) / [Builder](./index.md)

# Builder

`class Builder`

Used to create a new instance of the fragment.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Used to create a new instance of the fragment.`Builder()` |

### Functions

| Name | Summary |
|---|---|
| [allowCurrentLocation](allow-current-location.md) | The fragment can optionally show a static option of "Current Location".`fun allowCurrentLocation(withCurrentLocation: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true): Builder` |
| [allowDropPin](allow-drop-pin.md) | The fragment can optionally show a static option of "Choose on Map".`fun allowDropPin(withDropPin: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)` = true): Builder` |
| [build](build.md) | Finalize and build the Fragment`fun build(): `[`LocationSearchFragment`](../index.md) |
| [near](near.md) | Used for TripGo searches. For example, the center of a map.`fun near(near: LatLng?): Builder` |
| [withBounds](with-bounds.md) | Used for Google Places searches. For example, a map's visible boundaries.`fun withBounds(bounds: LatLngBounds?): Builder` |
| [withHint](with-hint.md) | Sets the EditText hint. For example, "Where do you want to go?"`fun withHint(hint: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): Builder` |
| [withInitialQuery](with-initial-query.md) | Sets the initial query.`fun withInitialQuery(initialQuery: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): Builder` |
