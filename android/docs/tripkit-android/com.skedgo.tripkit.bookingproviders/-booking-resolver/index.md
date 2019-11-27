[tripkit-android](../../index.md) / [com.skedgo.tripkit.bookingproviders](../index.md) / [BookingResolver](./index.md)

# BookingResolver

`interface BookingResolver`

### Properties

| Name | Summary |
|---|---|
| [FLITWAYS](-f-l-i-t-w-a-y-s.md) | `static val FLITWAYS: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [GOCATCH](-g-o-c-a-t-c-h.md) | `static val GOCATCH: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [INGOGO](-i-n-g-o-g-o.md) | `static val INGOGO: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [LYFT](-l-y-f-t.md) | `static val LYFT: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [MTAXI](-m-t-a-x-i.md) | `static val MTAXI: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [OTHERS](-o-t-h-e-r-s.md) | `static val OTHERS: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [SMS](-s-m-s.md) | `static val SMS: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [UBER](-u-b-e-r.md) | `static val UBER: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |

### Functions

| Name | Summary |
|---|---|
| [getTitleForExternalAction](get-title-for-external-action.md) | `abstract fun getTitleForExternalAction(externalAction: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [performExternalActionAsync](perform-external-action-async.md) | `abstract fun performExternalActionAsync(params: `[`ExternalActionParams`](../../com.skedgo.tripkit/-external-action-params/index.md)`!): Observable<`[`BookingAction`](../../com.skedgo.tripkit/-booking-action/index.md)`!>!` |

### Inheritors

| Name | Summary |
|---|---|
| [BookingResolverImpl](../-booking-resolver-impl/index.md) | `class BookingResolverImpl : `[`BookingResolver`](./index.md) |
| [UberBookingResolver](../-uber-booking-resolver/index.md) | `class UberBookingResolver : `[`BookingResolver`](./index.md) |
