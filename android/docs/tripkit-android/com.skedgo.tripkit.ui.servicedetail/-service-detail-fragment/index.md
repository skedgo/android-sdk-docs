[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.servicedetail](../index.md) / [ServiceDetailFragment](./index.md)

# ServiceDetailFragment

`class ServiceDetailFragment : `[`AbstractTripKitFragment`](../../com.skedgo.tripkit.ui.core/-abstract-trip-kit-fragment/index.md)

### Types

| Name | Summary |
|---|---|
| [Builder](-builder/index.md) | `class Builder` |
| [OnScheduledStopClickListener](-on-scheduled-stop-click-listener/index.md) | `interface OnScheduledStopClickListener` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ServiceDetailFragment()` |

### Properties

| Name | Summary |
|---|---|
| [binding](binding.md) | `lateinit var binding: <ERROR CLASS>` |
| [viewModel](view-model.md) | `lateinit var viewModel: `[`ServiceDetailViewModel`](../-service-detail-view-model/index.md) |

### Functions

| Name | Summary |
|---|---|
| [addOnScheduledStopClickListener](add-on-scheduled-stop-click-listener.md) | `fun addOnScheduledStopClickListener(callback: OnScheduledStopClickListener): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>`fun addOnScheduledStopClickListener(listener: (`[`ServiceStop`](../../com.skedgo.tripkit.common.model/-service-stop/index.md)`) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onActivityCreated](on-activity-created.md) | `fun onActivityCreated(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onAttach](on-attach.md) | `fun onAttach(context: Context): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreateView](on-create-view.md) | `fun onCreateView(inflater: LayoutInflater, container: ViewGroup?, savedInstanceState: Bundle?): View?` |
| [onViewCreated](on-view-created.md) | `fun onViewCreated(view: View, savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
