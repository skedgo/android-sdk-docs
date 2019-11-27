[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.search](../index.md) / [LocationSearchErrorViewModel](./index.md)

# LocationSearchErrorViewModel

`class LocationSearchErrorViewModel`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `LocationSearchErrorViewModel(context: Context)` |

### Properties

| Name | Summary |
|---|---|
| [actionText](action-text.md) | `val actionText: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [chooseOnMapObservable](choose-on-map-observable.md) | `val chooseOnMapObservable: Observable<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [context](context.md) | `val context: Context` |
| [iconSrc](icon-src.md) | `val iconSrc: ObservableField<Drawable>` |
| [retryObservable](retry-observable.md) | `val retryObservable: Observable<`[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`>` |
| [title](title.md) | `val title: ObservableField<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |

### Functions

| Name | Summary |
|---|---|
| [performAction](perform-action.md) | `fun performAction(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [updateError](update-error.md) | `fun updateError(errorType: `[`SearchErrorType`](../-search-error-type/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
