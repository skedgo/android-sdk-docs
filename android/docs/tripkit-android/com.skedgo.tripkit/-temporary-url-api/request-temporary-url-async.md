[tripkit-android](../../index.md) / [com.skedgo.tripkit](../index.md) / [TemporaryUrlApi](index.md) / [requestTemporaryUrlAsync](./request-temporary-url-async.md)

# requestTemporaryUrlAsync

`@GET abstract fun requestTemporaryUrlAsync(@Url url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, @QueryMap config: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!, `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`!>!): Observable<`[`RoutingResponse`](../../com.skedgo.tripkit.routing/-routing-response/index.md)`!>!`

### Parameters

`url` - [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!: Should be ``[`Trip#getTemporaryURL()`](../../com.skedgo.tripkit.routing/-trip/get-temporary-u-r-l.md).

`config` - [MutableMap](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!,&nbsp;[Any](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)!&gt;!: Described in [Default configuration parameters](https://redmine.buzzhives.com/projects/buzzhives/wiki/Main_API_formats#Default-configuration-parameters).