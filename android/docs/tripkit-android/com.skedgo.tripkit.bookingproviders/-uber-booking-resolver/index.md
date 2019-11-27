[tripkit-android](../../index.md) / [com.skedgo.tripkit.bookingproviders](../index.md) / [UberBookingResolver](./index.md)

# UberBookingResolver

`class UberBookingResolver : `[`BookingResolver`](../-booking-resolver/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `UberBookingResolver(isPackageInstalled: Function<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`>, getAppIntent: Function<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, Intent>)` |

### Functions

| Name | Summary |
|---|---|
| [getTitleForExternalAction](get-title-for-external-action.md) | `fun getTitleForExternalAction(externalAction: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [performExternalActionAsync](perform-external-action-async.md) | `fun performExternalActionAsync(params: `[`ExternalActionParams`](../../com.skedgo.tripkit/-external-action-params/index.md)`): Observable<`[`BookingAction`](../../com.skedgo.tripkit/-booking-action/index.md)`>` |
