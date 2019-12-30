[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.model](../index.md) / [BookingConfirmationStatus](./index.md)

# BookingConfirmationStatus

`@TypeAdapters @Immutable abstract class BookingConfirmationStatus : Parcelable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BookingConfirmationStatus()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`BookingConfirmationStatus`](./index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [subtitle](subtitle.md) | `abstract fun subtitle(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [title](title.md) | `abstract fun title(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [value](value.md) | `abstract fun value(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(dest: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
