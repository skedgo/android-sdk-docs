[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.model](../index.md) / [BookingSource](./index.md)

# BookingSource

`@TypeAdapters @Immutable abstract class BookingSource : Parcelable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BookingSource()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`BookingSource`](./index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [provider](provider.md) | `abstract fun provider(): `[`BookingProvider`](../-booking-provider/index.md)`?` |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(dest: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
