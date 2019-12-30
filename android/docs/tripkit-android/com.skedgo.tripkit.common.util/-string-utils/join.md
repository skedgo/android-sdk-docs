[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.util](../index.md) / [StringUtils](index.md) / [join](./join.md)

# join

`static fun join(strings: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!``static fun join(strings: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!, separator: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!`

Joins the elements of the provided List into a single String containing the provided elements.

### Parameters

`strings` - [MutableList](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)&lt;[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!&gt;!: The List of values to join together, may be null

`separator` - [String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!: The separator character to use

**Return**
[String](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)!: The joined String, empty if null List input

