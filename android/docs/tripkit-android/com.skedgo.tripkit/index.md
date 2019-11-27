[tripkit-android](../index.md) / [com.skedgo.tripkit](./index.md)

## Package com.skedgo.tripkit

### Types

| Name | Summary |
|---|---|
| [AndroidGeocoder](-android-geocoder/index.md) | `class AndroidGeocoder : `[`ReverseGeocodable`](../skedgo.tripkit.geocoding/-reverse-geocodable/index.md) |
| [BookingAction](-booking-action/index.md) | `abstract class BookingAction` |
| [CarPark](-car-park/index.md) | `abstract class CarPark` |
| [Co2Preferences](-co2-preferences/index.md) | `interface Co2Preferences` |
| [Configs](-configs/index.md) | `abstract class Configs` |
| [DefaultCo2Preferences](-default-co2-preferences/index.md) | `class DefaultCo2Preferences : `[`Co2Preferences`](-co2-preferences/index.md) |
| [DefaultTripPreferences](-default-trip-preferences/index.md) | `class DefaultTripPreferences : `[`TripPreferences`](-trip-preferences/index.md) |
| [ExternalActionParams](-external-action-params/index.md) | `abstract class ExternalActionParams` |
| [HttpClientModule](-http-client-module/index.md) | `open class HttpClientModule` |
| [LineSegment](-line-segment/index.md) | Represents a segment of a polyline denoting a ``[`Trip`](../skedgo.tripkit.routing/-trip/index.md).`class LineSegment` |
| [LocationInfo](-location-info/index.md) | `interface LocationInfo` |
| [LocationInfoDetails](-location-info-details/index.md) | `abstract class LocationInfoDetails` |
| [LocationInfoService](-location-info-service/index.md) | `interface LocationInfoService` |
| [MainModule](-main-module/index.md) | `open class MainModule` |
| [PeriodicRealTimeTripUpdateReceiver](-periodic-real-time-trip-update-receiver/index.md) | `abstract class PeriodicRealTimeTripUpdateReceiver : `[`RealTimeTripUpdateReceiver`](-real-time-trip-update-receiver/index.md) |
| [QueryGenerator](-query-generator.md) | `interface QueryGenerator : BiFunction<`[`Query`](../com.skedgo.android.common.model/-query/index.md)`, `[`TransportModeFilter`](-transport-mode-filter/index.md)`, Observable<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`Query`](../com.skedgo.android.common.model/-query/index.md)`>>>` |
| [RealTimeTripUpdateReceiver](-real-time-trip-update-receiver/index.md) | `interface RealTimeTripUpdateReceiver` |
| [ServiceApi](-service-api/index.md) | `interface ServiceApi` |
| [ServiceExtras](-service-extras/index.md) | `class ServiceExtras` |
| [ServiceResponse](-service-response/index.md) | `interface ServiceResponse` |
| [TemporaryUrlApi](-temporary-url-api/index.md) | Handles downloading trip via ``[`Trip#getTemporaryURL()`](../skedgo.tripkit.routing/-trip/get-temporary-u-r-l.md).`interface TemporaryUrlApi` |
| [TransitModeFilter](-transit-mode-filter/index.md) | `interface TransitModeFilter` |
| [TransitService](-transit-service/index.md) | `interface TransitService` |
| [TransportModeFilter](-transport-mode-filter/index.md) | `interface TransportModeFilter` |
| [TripPreferences](-trip-preferences/index.md) | `interface TripPreferences` |
| [TripRegionResolver](-trip-region-resolver/index.md) | `abstract class TripRegionResolver : BiFunction<`[`Location`](../com.skedgo.android.common.model/-location/index.md)`!, `[`Location`](../com.skedgo.android.common.model/-location/index.md)`!, Observable<`[`Region`](../com.skedgo.android.common.model/-region/index.md)`!>!>` |
| [TripUpdater](-trip-updater/index.md) | `interface TripUpdater` |

### Exceptions

| Name | Summary |
|---|---|
| [NoConnectionError](-no-connection-error/index.md) | `class NoConnectionError : `[`RoutingError`](-routing-error.md) |
| [OutOfRegionsException](-out-of-regions-exception/index.md) | `class OutOfRegionsException : `[`RuntimeException`](https://docs.oracle.com/javase/7/docs/api/java/lang/RuntimeException.html) |
| [RoutingError](-routing-error.md) | `sealed class RoutingError : `[`RuntimeException`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-runtime-exception/index.html) |
| [RoutingUserError](-routing-user-error/index.md) | `class RoutingUserError : `[`RoutingError`](-routing-error.md) |
