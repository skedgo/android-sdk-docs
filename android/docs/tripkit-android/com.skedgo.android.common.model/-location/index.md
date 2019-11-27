[tripkit-android](../../index.md) / [com.skedgo.android.common.model](../index.md) / [Location](./index.md)

# Location

`open class Location : Parcelable`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Location()`<br>`Location(other: `[`Location`](./index.md)`!)`<br>`Location(lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lon: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`)` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`Location`](./index.md)`!>!` |
| [FOURSQUARE](-f-o-u-r-s-q-u-a-r-e.md) | `static val FOURSQUARE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [GOOGLE](-g-o-o-g-l-e.md) | `static val GOOGLE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [LOCAL](-l-o-c-a-l.md) | `static val LOCAL: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [mAverageRating](m-average-rating.md) | `var mAverageRating: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [mFavouriteSortOrderIndex](m-favourite-sort-order-index.md) | `var mFavouriteSortOrderIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [mId](m-id.md) | `var mId: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [mIsFavourite](m-is-favourite.md) | `var mIsFavourite: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [mLocationType](m-location-type.md) | `var mLocationType: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [mRatingCount](m-rating-count.md) | `var mRatingCount: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [mRatingImageUrl](m-rating-image-url.md) | `var mRatingImageUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [mSource](m-source.md) | `var mSource: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [NO_BEARING](-n-o_-b-e-a-r-i-n-g.md) | `static val NO_BEARING: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [TRIPGO](-t-r-i-p-g-o.md) | Source`static val TRIPGO: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [TYPE_CALENDAR](-t-y-p-e_-c-a-l-e-n-d-a-r.md) | Location comes from users calendar`static val TYPE_CALENDAR: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [TYPE_CONTACT](-t-y-p-e_-c-o-n-t-a-c-t.md) | Location comes from a contact in the users address book`static val TYPE_CONTACT: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [TYPE_HISTORY](-t-y-p-e_-h-i-s-t-o-r-y.md) | Location comes from previous search/geocoding history or long-pressed`static val TYPE_HISTORY: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [TYPE_HOME](-t-y-p-e_-h-o-m-e.md) | Location is info from the users personal contact card (home/work address etc)`static val TYPE_HOME: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [TYPE_PERSONAL](-t-y-p-e_-p-e-r-s-o-n-a-l.md) | Location is info from the users personal contact card (home/work address etc)`static val TYPE_PERSONAL: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [TYPE_SCHEDULED_STOP](-t-y-p-e_-s-c-h-e-d-u-l-e-d_-s-t-o-p.md) | The location is a scheduled stop`static val TYPE_SCHEDULED_STOP: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [TYPE_SERVICE_STOP](-t-y-p-e_-s-e-r-v-i-c-e_-s-t-o-p.md) | Location is a stop on a user's trip`static val TYPE_SERVICE_STOP: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [TYPE_UNKNOWN](-t-y-p-e_-u-n-k-n-o-w-n.md) | No known location type`static val TYPE_UNKNOWN: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [TYPE_W3W](-t-y-p-e_-w3-w.md) | What3Words type`static val TYPE_W3W: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [TYPE_WORK](-t-y-p-e_-w-o-r-k.md) | `static val TYPE_WORK: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [ZERO_LAT](-z-e-r-o_-l-a-t.md) | `static val ZERO_LAT: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [ZERO_LON](-z-e-r-o_-l-o-n.md) | `static val ZERO_LON: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |

### Functions

| Name | Summary |
|---|---|
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [distanceTo](distance-to.md) | `open fun distanceTo(location: `[`Location`](./index.md)`!): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)<br>Get the distance between this and another point `open fun distanceTo(lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lon: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [equals](equals.md) | `open fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [equalsByLatLon](equals-by-lat-lon.md) | `open fun equalsByLatLon(_loc: `[`Location`](./index.md)`!): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [fillFrom](fill-from.md) | `open fun fillFrom(other: `[`Location`](./index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getAddress](get-address.md) | `open fun getAddress(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getAverageRating](get-average-rating.md) | `open fun getAverageRating(): `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |
| [getBearing](get-bearing.md) | `open fun getBearing(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getBearingTo](get-bearing-to.md) | `open fun getBearingTo(other: `[`Location`](./index.md)`!): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)<br>`open fun getBearingTo(lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lon: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getCoordinateString](get-coordinate-string.md) | `open fun getCoordinateString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getDisplayAddress](get-display-address.md) | `open fun getDisplayAddress(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getDisplayName](get-display-name.md) | To present a human-readable name of a location. Invoke this if we want to present a location to users (e.g, a pin on a map, location of an event).`open fun getDisplayName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getFavouriteSortOrderIndex](get-favourite-sort-order-index.md) | `open fun getFavouriteSortOrderIndex(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getId](get-id.md) | `open fun getId(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getLastUpdatedTime](get-last-updated-time.md) | `open fun getLastUpdatedTime(): `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html) |
| [getLat](get-lat.md) | `open fun getLat(): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getLocationClass](get-location-class.md) | `open fun getLocationClass(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getLocationType](get-location-type.md) | `open fun getLocationType(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getLon](get-lon.md) | `open fun getLon(): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [getName](get-name.md) | `open fun getName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getNameOrApproximateAddress](get-name-or-approximate-address.md) | `open fun getNameOrApproximateAddress(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getPhoneNumber](get-phone-number.md) | `open fun getPhoneNumber(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getPopularity](get-popularity.md) | `open fun getPopularity(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getRatingCount](get-rating-count.md) | `open fun getRatingCount(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getRatingImageUrl](get-rating-image-url.md) | `open fun getRatingImageUrl(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getSource](get-source.md) | `open fun getSource(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getUrl](get-url.md) | `open fun getUrl(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getW3w](get-w3w.md) | `open fun getW3w(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getW3wInfoURL](get-w3w-info-u-r-l.md) | `open fun getW3wInfoURL(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [hasValidCoordinates](has-valid-coordinates.md) | `open fun hasValidCoordinates(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isApproximatelyAt](is-approximately-at.md) | `open fun isApproximatelyAt(other: `[`Location`](./index.md)`!): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>`open fun isApproximatelyAt(lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`, lon: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isExact](is-exact.md) | `open fun isExact(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isFavourite](is-favourite.md) | `open fun isFavourite(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)<br>`open fun isFavourite(favourite: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [isLooselyApproximatelyAt](is-loosely-approximately-at.md) | `open fun isLooselyApproximatelyAt(other: `[`Location`](./index.md)`!): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isNonZeroLocation](is-non-zero-location.md) | `open fun isNonZeroLocation(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [isValidLocation](is-valid-location.md) | `open static fun isValidLocation(loc: `[`Location`](./index.md)`!): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [round](round.md) | `open fun round(d: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html) |
| [setAddress](set-address.md) | `open fun setAddress(address: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setAverageRating](set-average-rating.md) | `open fun setAverageRating(averageRating: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setBearing](set-bearing.md) | `open fun setBearing(bearing: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setExact](set-exact.md) | `open fun setExact(exact: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setFavouriteSortOrderIndex](set-favourite-sort-order-index.md) | `open fun setFavouriteSortOrderIndex(favouriteSortOrderIndex: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setId](set-id.md) | `open fun setId(id: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setLastUpdatedTime](set-last-updated-time.md) | `open fun setLastUpdatedTime(lastUpdatedTime: `[`Long`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-long/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setLat](set-lat.md) | `open fun setLat(lat: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setLocationClass](set-location-class.md) | `open fun setLocationClass(locationClass: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setLocationType](set-location-type.md) | `open fun setLocationType(type: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setLon](set-lon.md) | `open fun setLon(lon: `[`Double`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-double/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setName](set-name.md) | `open fun setName(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setPhoneNumber](set-phone-number.md) | `open fun setPhoneNumber(phoneNumber: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setPopularity](set-popularity.md) | `open fun setPopularity(popularity: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRatingCount](set-rating-count.md) | `open fun setRatingCount(ratingCount: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRatingImageUrl](set-rating-image-url.md) | `open fun setRatingImageUrl(ratingImageUrl: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setSource](set-source.md) | `open fun setSource(source: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTimeZone](set-time-zone.md) | NOTE: You should only use this setter for testing purpose.`open fun setTimeZone(timeZone: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setUrl](set-url.md) | `open fun setUrl(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setW3w](set-w3w.md) | `open fun setW3w(w3w: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setW3wInfoURL](set-w3w-info-u-r-l.md) | `open fun setW3wInfoURL(w3wInfoURL: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(out: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Properties

| Name | Summary |
|---|---|
| [dateTimeZone](../../skedgo.tripkit.routing/date-time-zone.md) | `val `[`Location`](./index.md)`.dateTimeZone: DateTimeZone` |

### Extension Functions

| Name | Summary |
|---|---|
| [isNear](../../skedgo.tripkit.routing/is-near.md) | `fun `[`Location`](./index.md)`.isNear(location: `[`Location`](./index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [ScheduledStop](../-scheduled-stop/index.md) | `open class ScheduledStop : `[`Location`](./index.md) |
| [ServiceStop](../-service-stop/index.md) | Represents a future stop of a service in a trip.`open class ServiceStop : `[`Location`](./index.md)`, `[`WheelchairAccessible`](../-wheelchair-accessible/index.md) |
