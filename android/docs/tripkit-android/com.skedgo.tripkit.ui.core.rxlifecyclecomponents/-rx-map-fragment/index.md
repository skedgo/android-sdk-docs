[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.core.rxlifecyclecomponents](../index.md) / [RxMapFragment](./index.md)

# RxMapFragment

`abstract class RxMapFragment : SupportMapFragment, LifecycleProvider<`[`FragmentEvent`](../-fragment-event/index.md)`>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `RxMapFragment()` |

### Functions

| Name | Summary |
|---|---|
| [bindToLifecycle](bind-to-lifecycle.md) | `open fun <T> bindToLifecycle(): LifecycleTransformer<T>` |
| [bindUntilEvent](bind-until-event.md) | `open fun <T> bindUntilEvent(event: `[`FragmentEvent`](../-fragment-event/index.md)`): LifecycleTransformer<T>` |
| [lifecycle](lifecycle.md) | `open fun lifecycle(): Observable<`[`FragmentEvent`](../-fragment-event/index.md)`>` |
| [onAttach](on-attach.md) | `open fun onAttach(context: Context): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onCreate](on-create.md) | `open fun onCreate(savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onDestroy](on-destroy.md) | `open fun onDestroy(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onDestroyView](on-destroy-view.md) | `open fun onDestroyView(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onDetach](on-detach.md) | `open fun onDetach(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onPause](on-pause.md) | `open fun onPause(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onResume](on-resume.md) | `open fun onResume(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStart](on-start.md) | `open fun onStart(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onStop](on-stop.md) | `open fun onStop(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onViewCreated](on-view-created.md) | `open fun onViewCreated(view: View, savedInstanceState: Bundle?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [BaseMapFragment](../../com.skedgo.tripkit.ui.map/-base-map-fragment/index.md) | `abstract class BaseMapFragment : `[`RxMapFragment`](./index.md) |
