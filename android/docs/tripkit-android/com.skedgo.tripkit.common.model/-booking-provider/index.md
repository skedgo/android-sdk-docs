[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.model](../index.md) / [BookingProvider](./index.md)

# BookingProvider

`@TypeAdapters @Immutable abstract class BookingProvider : Parcelable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BookingProvider()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`BookingProvider`](./index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [color](color.md) | `abstract fun color(): `[`ServiceColor`](../../com.skedgo.tripkit.routing/-service-color/index.md)`?` |
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [name](name.md) | `abstract fun name(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [phone](phone.md) | `abstract fun phone(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [remoteDarkIcon](remote-dark-icon.md) | `abstract fun remoteDarkIcon(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [remoteIcon](remote-icon.md) | `abstract fun remoteIcon(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [website](website.md) | `abstract fun website(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(dest: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
