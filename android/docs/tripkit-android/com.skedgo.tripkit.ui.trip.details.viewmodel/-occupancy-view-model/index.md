[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.trip.details.viewmodel](../index.md) / [OccupancyViewModel](./index.md)

# OccupancyViewModel

`open class OccupancyViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `OccupancyViewModel(context: Context)` |

### Properties

| Name | Summary |
|---|---|
| [background](background.md) | `val background: ObservableField<Drawable?>` |
| [drawableLeft](drawable-left.md) | `val drawableLeft: ObservableField<Drawable>` |
| [hasOccupancyInformation](has-occupancy-information.md) | `val hasOccupancyInformation: ObservableBoolean` |
| [hasOccupancySingleInformation](has-occupancy-single-information.md) | `val hasOccupancySingleInformation: ObservableBoolean` |
| [itemBinding](item-binding.md) | `val itemBinding: ItemBinding<`[`TrainOccupancyItemViewModel`](../-train-occupancy-item-view-model/index.md)`!>` |
| [items](items.md) | `val items: ObservableList<`[`TrainOccupancyItemViewModel`](../-train-occupancy-item-view-model/index.md)`>` |
| [occupancyText](occupancy-text.md) | `val occupancyText: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [hasInformation](has-information.md) | `fun hasInformation(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setOccupancy](set-occupancy.md) | `open fun setOccupancy(vehicle: `[`RealTimeVehicle`](../../com.skedgo.tripkit.routing/-real-time-vehicle/index.md)`, showAverage: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
