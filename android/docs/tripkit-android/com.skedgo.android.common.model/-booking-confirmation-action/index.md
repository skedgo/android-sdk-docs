[tripkit-android](../../index.md) / [com.skedgo.android.common.model](../index.md) / [BookingConfirmationAction](./index.md)

# BookingConfirmationAction

`@TypeAdapters @Immutable abstract class BookingConfirmationAction : Parcelable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BookingConfirmationAction()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`BookingConfirmationAction`](./index.md)`!>!` |
| [TYPE_CALL](-t-y-p-e_-c-a-l-l.md) | `static val TYPE_CALL: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [TYPE_CANCEL](-t-y-p-e_-c-a-n-c-e-l.md) | `static val TYPE_CANCEL: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [TYPE_QR_CODE](-t-y-p-e_-q-r_-c-o-d-e.md) | `static val TYPE_QR_CODE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [externalURL](external-u-r-l.md) | `abstract fun externalURL(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [internalURL](internal-u-r-l.md) | `abstract fun internalURL(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [isDestructive](is-destructive.md) | `abstract fun isDestructive(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [title](title.md) | `abstract fun title(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [type](type.md) | `abstract fun type(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(dest: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
