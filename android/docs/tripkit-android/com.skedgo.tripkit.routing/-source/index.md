[tripkit-android](../../index.md) / [com.skedgo.tripkit.routing](../index.md) / [Source](./index.md)

# Source

`@TypeAdapters @Immutable abstract class Source : Parcelable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Source()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`Source`](./index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [disclaimer](disclaimer.md) | `abstract fun disclaimer(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [provider](provider.md) | `abstract fun provider(): `[`Provider`](../-provider/index.md)`?` |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(dest: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
