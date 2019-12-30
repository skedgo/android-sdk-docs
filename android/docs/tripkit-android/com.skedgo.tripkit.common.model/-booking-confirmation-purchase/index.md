[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.model](../index.md) / [BookingConfirmationPurchase](./index.md)

# BookingConfirmationPurchase

`@TypeAdapters @Immutable abstract class BookingConfirmationPurchase : Parcelable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `BookingConfirmationPurchase()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`BookingConfirmationPurchase`](./index.md)`!>!` |

### Functions

| Name | Summary |
|---|---|
| [brand](brand.md) | `abstract fun brand(): `[`PurchaseBrand`](../-purchase-brand/index.md)`?` |
| [currency](currency.md) | `abstract fun currency(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [id](id.md) | `abstract fun id(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [price](price.md) | `abstract fun price(): `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [productName](product-name.md) | `abstract fun productName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [productType](product-type.md) | `abstract fun productType(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [source](source.md) | `abstract fun source(): `[`BookingSource`](../-booking-source/index.md)`?` |
| [timezone](timezone.md) | `abstract fun timezone(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [valid](valid.md) | `open fun valid(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [validFor](valid-for.md) | `open fun validFor(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [validFrom](valid-from.md) | `open fun validFrom(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(dest: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
