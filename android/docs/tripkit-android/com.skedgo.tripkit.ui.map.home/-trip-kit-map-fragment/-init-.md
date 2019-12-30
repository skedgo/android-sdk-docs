[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.map.home](../index.md) / [TripKitMapFragment](index.md) / [&lt;init&gt;](./-init-.md)

# &lt;init&gt;

`TripKitMapFragment()`

A map component for an app. It automatically integrates with SkedGo's backend, display transit information without any additional intervention. Being a fragment, it can very easily be added to an activity's layout.

```
<fragment
              android:layout_width="match_parent"
              android:layout_height="match_parent"
              android:id="@+id/map"
              android:name="com.skedgo.tripkit.ui.map.home.TripKitMapFragment"/>
```

 Your app **must** provide a TripGo API token as `R.string.skedgo_api_key`.

