[tripkit-android](../../index.md) / [com.skedgo.tripkit.a2brouting](../index.md) / [SelectBestDisplayTrip](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`SelectBestDisplayTrip()`

Selects display trip which has lowest weighted score.

 If we leave after a certain query time, this helps pick the best display trip having start time that is not before the query time. Also, if we arrive by, it makes sure that display trip having end time which is after the query time will not be selected.