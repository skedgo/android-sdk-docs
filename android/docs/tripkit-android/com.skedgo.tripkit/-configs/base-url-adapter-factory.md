[tripkit-android](../../index.md) / [com.skedgo.tripkit](../index.md) / [Configs](index.md) / [baseUrlAdapterFactory](./base-url-adapter-factory.md)

# baseUrlAdapterFactory

`@Nullable abstract fun baseUrlAdapterFactory(): `[`Callable`](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Callable.html)`<`[`Callable`](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Callable.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!>?`

**Return**
[Callable](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Callable.html)&lt;[Callable](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Callable.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!&gt;!&gt;?: A factory to create a sort of adapter that specifies a base url to override all the 'satapp' requests made by TripKit's apis. The factory is in use only when ``[`#debuggable()`](debuggable.md) is true.

