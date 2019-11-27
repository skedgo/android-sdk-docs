[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.core.rxlifecyclecomponents](../index.md) / [RxLifecycleAndroid](index.md) / [bindActivity](./bind-activity.md)

# bindActivity

`@NonNull @CheckResult fun <T> bindActivity(@NonNull lifecycle: Observable<`[`ActivityEvent`](../-activity-event/index.md)`>): LifecycleTransformer<T>`

Binds the given source to an Activity lifecycle.

Use with [Observable.compose](#):
`source.compose(RxLifecycleAndroid.bindActivity(lifecycle)).subscribe()`

This helper automatically determines (based on the lifecycle sequence itself) when the source
should stop emitting items. In the case that the lifecycle sequence is in the
creation phase (CREATE, START, etc) it will choose the equivalent destructive phase (DESTROY,
STOP, etc). If used in the destructive phase, the notifications will cease at the next event;
for example, if used in PAUSE, it will unsubscribe in STOP.

Due to the differences between the Activity and Fragment lifecycles, this method should only
be used for an Activity lifecycle.

### Parameters

`lifecycle` - the lifecycle sequence of an Activity

**Return**
a reusable [Observable.Transformer](#) that unsubscribes the source during the Activity lifecycle

