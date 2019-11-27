[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.core.rxlifecyclecomponents](../index.md) / [RxLifecycleAndroid](index.md) / [bindFragment](./bind-fragment.md)

# bindFragment

`@CheckResult fun <T> bindFragment(lifecycle: Observable<`[`FragmentEvent`](../-fragment-event/index.md)`>): LifecycleTransformer<T>`

Binds the given source to a Fragment lifecycle.

Use with [Observable.compose](#):
`source.compose(RxLifecycleAndroid.bindFragment(lifecycle)).subscribe()`

This helper automatically determines (based on the lifecycle sequence itself) when the source
should stop emitting items. In the case that the lifecycle sequence is in the
creation phase (CREATE, START, etc) it will choose the equivalent destructive phase (DESTROY,
STOP, etc). If used in the destructive phase, the notifications will cease at the next event;
for example, if used in PAUSE, it will unsubscribe in STOP.

Due to the differences between the Activity and Fragment lifecycles, this method should only
be used for a Fragment lifecycle.

### Parameters

`lifecycle` - the lifecycle sequence of a Fragment

**Return**
a reusable [Observable.Transformer](#) that unsubscribes the source during the Fragment lifecycle

