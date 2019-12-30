[tripkit-android](../../index.md) / [com.skedgo.tripkit.routing](../index.md) / [TripGroupComparators](index.md) / [DEPARTURE_COMPARATOR_CHAIN](./-d-e-p-a-r-t-u-r-e_-c-o-m-p-a-r-a-t-o-r_-c-h-a-i-n.md)

# DEPARTURE_COMPARATOR_CHAIN

`static val DEPARTURE_COMPARATOR_CHAIN: `[`Comparator`](https://docs.oracle.com/javase/7/docs/api/java/util/Comparator.html)`<`[`TripGroup`](../-trip-group/index.md)`!>!`

To sort routes by arrive-by query.

 Q: Why reverse departure time? A: "If it's an arrive-by query and you sort by time, you don't care when the trips arrive as you told them when they should arrive. What matters is when they leave. Trips that leave later (while arriving before the time you selected) are better. Hence: sort descending by arrival time." (Adrian said)

**See Also**
&lt;a href="https://redmine.buzzhives.com/issues/3967"&gt;Discussion&lt;/a&gt;

