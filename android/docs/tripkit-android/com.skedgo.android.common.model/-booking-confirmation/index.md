[tripkit-android](../../index.md) / [com.skedgo.android.common.model](../index.md) / [BookingConfirmation](./index.md)

# BookingConfirmation

`@TypeAdapters @Immutable abstract class BookingConfirmation : Parcelable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BookingConfirmation()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`BookingConfirmation`](./index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [actions](actions.md) | `abstract fun actions(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`BookingConfirmationAction`](../-booking-confirmation-action/index.md)`!>!` |
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [provider](provider.md) | `abstract fun provider(): `[`BookingConfirmationImage`](../-booking-confirmation-image/index.md)`?` |
| [purchase](purchase.md) | `abstract fun purchase(): `[`BookingConfirmationPurchase`](../-booking-confirmation-purchase/index.md)`?` |
| [status](status.md) | `abstract fun status(): `[`BookingConfirmationStatus`](../-booking-confirmation-status/index.md)`!` |
| [vehicle](vehicle.md) | `abstract fun vehicle(): `[`BookingConfirmationImage`](../-booking-confirmation-image/index.md)`?` |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(dest: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
