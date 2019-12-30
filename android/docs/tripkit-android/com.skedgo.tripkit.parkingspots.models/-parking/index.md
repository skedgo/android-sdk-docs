[tripkit-android](../../index.md) / [com.skedgo.tripkit.parkingspots.models](../index.md) / [Parking](./index.md)

# Parking

`sealed class Parking`

### Types

| Name | Summary |
|---|---|
| [Vacancy](-vacancy/index.md) | `enum class Vacancy` |

### Properties

| Name | Summary |
|---|---|
| [address](address.md) | `val address: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [id](id.md) | `val id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [info](info.md) | `val info: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [location](location.md) | `val location: `[`GeoPoint`](../../com.skedgo.tripkit.location/-geo-point/index.md) |
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [parkingOperator](parking-operator.md) | `val parkingOperator: `[`ParkingOperator`](../-parking-operator/index.md) |
| [parkingVacancy](parking-vacancy.md) | `val parkingVacancy: Vacancy` |

### Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | `open fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [hashCode](hash-code.md) | `open fun hashCode(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [OffStreetParking](../-off-street-parking/index.md) | `open class OffStreetParking : `[`Parking`](./index.md) |
| [OnStreetParking](../-on-street-parking/index.md) | `class OnStreetParking : `[`Parking`](./index.md) |
