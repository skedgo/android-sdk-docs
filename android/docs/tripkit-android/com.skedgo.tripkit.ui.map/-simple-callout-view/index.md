[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map](../index.md) / [SimpleCalloutView](./index.md)

# SimpleCalloutView

`class SimpleCalloutView : LinearLayout`

View to create custom callout in ``[`InfoWindowAdapter`](#), simply including a title, a snippet, a left image and a right image.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | Should not invoke this constructor directly. Use ``[`#create(LayoutInflater)`](create.md) instead.`SimpleCalloutView(context: Context!)``SimpleCalloutView(context: Context!, attrs: AttributeSet!)`<br>`SimpleCalloutView(context: Context!, attrs: AttributeSet!, defStyleAttr: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)`<br>`SimpleCalloutView(context: Context!, attrs: AttributeSet!, defStyleAttr: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, defStyleRes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`)` |

### Functions

| Name | Summary |
|---|---|
| [create](create.md) | `static fun create(inflater: LayoutInflater): `[`SimpleCalloutView`](./index.md)`!` |
| [onFinishInflate](on-finish-inflate.md) | `fun onFinishInflate(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setLeftImage](set-left-image.md) | `fun setLeftImage(res: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRightImage](set-right-image.md) | `fun setRightImage(res: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSnippet](set-snippet.md) | `fun setSnippet(snippet: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTitle](set-title.md) | `fun setTitle(title: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
