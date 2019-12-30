[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.model](../index.md) / [AlertAction](./index.md)

# AlertAction

`@Immutable @TypeAdapters abstract class AlertAction : Parcelable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AlertAction()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`AlertAction`](./index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [excludedStopCodes](excluded-stop-codes.md) | `abstract fun excludedStopCodes(): `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>?` |
| [text](text.md) | `abstract fun text(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [type](type.md) | `abstract fun type(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(out: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
