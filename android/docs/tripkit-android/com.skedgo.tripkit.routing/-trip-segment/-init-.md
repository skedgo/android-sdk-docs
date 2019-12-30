[tripkit-android](../../index.md) / [com.skedgo.tripkit.routing](../index.md) / [TripSegment](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`TripSegment()`

To go from A to B, sometimes we have to travel X, Y, Z locations between A and B. That means, we travel A to X, then X to Y, then Y to Z, then Z to B which is the destination. To show how to travel from A to X, we use ``[`TripSegment`](index.md). So, in this case, a trip from A to B comprises 6 segments: - A segment whose type is ``[`SegmentType#DEPARTURE`](../-segment-type/-d-e-p-a-r-t-u-r-e.md). - A segment from A to X. - A segment from X to Y. - A segment from Y to Z. - A segment from Z to B. - A segment whose type is ``[`SegmentType#ARRIVAL`](../-segment-type/-a-r-r-i-v-a-l.md).

 Note that, to avoid ``[`TransactionTooLargeException`](#), it's discouraged to pass any instance of ``[`Query`](../../com.skedgo.tripkit.common.model/-query/index.md) to ``[`Intent`](#) or ``[`Bundle`](#). The ``[`Parcelable`](#) is subject to deletion at anytime.

**See Also**
&lt;a href="http://skedgo.github.io/tripgo-api/site/faq/#trips-groups-frequencies-and-templates"&gt;Trips, groups, frequencies and templates&lt;/a&gt;

