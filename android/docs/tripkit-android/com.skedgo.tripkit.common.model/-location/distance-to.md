[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.model](../index.md) / [Location](index.md) / [distanceTo](./distance-to.md)

# distanceTo

`open fun distanceTo(location: `[`Location`](index.md)`!): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`open fun distanceTo(lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lon: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)

Get the distance between this and another point

 This implementation was pulled from: [CodeCodex](http://www.codecodex.com/wiki/Calculate_Distance_Between_Two_Points_on_a_Globe#Java)

### Parameters

`lat` - [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html):

`lon` - [Double](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html):

**Return**
[Int](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html): The distance in meters between `this` and `that`

**See Also**
&lt;a href="http://en.wikipedia.org/wiki/Haversine_formula"&gt;Haversine Formula&lt;/a&gt;

