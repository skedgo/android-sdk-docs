[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.tripresult](../index.md) / [TripGroupsPagerAdapter](./index.md)

# TripGroupsPagerAdapter

`open class TripGroupsPagerAdapter : FragmentStatePagerAdapter`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TripGroupsPagerAdapter(fragmentManager: FragmentManager!)` |

### Properties

| Name | Summary |
|---|---|
| [listener](listener.md) | `var listener: OnTripKitButtonClickListener!` |

### Functions

| Name | Summary |
|---|---|
| [getCount](get-count.md) | `open fun getCount(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getItem](get-item.md) | `open fun getItem(position: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): Fragment` |
| [getTripGroups](get-trip-groups.md) | `open fun getTripGroups(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`!>!` |
| [setButtons](set-buttons.md) | `open fun setButtons(buttons: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripKitButton`](../../com.skedgo.tripkit.ui.model/-trip-kit-button/index.md)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTripGroups](set-trip-groups.md) | `open fun setTripGroups(tripGroups: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`TripGroup`](../../skedgo.tripkit.routing/-trip-group/index.md)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
