[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.timetables.domain](../index.md) / [TimetableLoaderFactory](index.md) / [createForSegment](./create-for-segment.md)

# createForSegment

`fun createForSegment(context: Context, pairIdentifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, sinceSecs: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): CursorLoader`

Creates a loader which is used to load A2B timetable from database.

### Parameters

`segment` - Should be a public transport segment (aka scheduled segment)