[tripkit-android](../../index.md) / [skedgo.tripkit.routing](../index.md) / [ModeInfo](./index.md)

# ModeInfo

`open class ModeInfo : Parcelable`

**See Also**
&lt;a href="http://skedgo.github.io/tripgo-api/site/faq/#mode-identifiers"&gt;Mode Identifiers&lt;/a&gt;

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `ModeInfo()` |

### Properties

| Name | Summary |
|---|---|
| [CREATOR](-c-r-e-a-t-o-r.md) | `static val CREATOR: Creator<`[`ModeInfo`](./index.md)`!>!` |
| [MAP_LIST_SIZE_RATIO](-m-a-p_-l-i-s-t_-s-i-z-e_-r-a-t-i-o.md) | `static val MAP_LIST_SIZE_RATIO: `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html) |

### Functions

| Name | Summary |
|---|---|
| [describeContents](describe-contents.md) | `open fun describeContents(): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getAlternativeText](get-alternative-text.md) | Indicates a human-readable name of the transport (e.g, "Train").`open fun getAlternativeText(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [getColor](get-color.md) | `open fun getColor(): `[`ServiceColor`](../-service-color/index.md)`?` |
| [getDescription](get-description.md) | `open fun getDescription(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getId](get-id.md) | `open fun getId(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getLocalIconName](get-local-icon-name.md) | `open fun getLocalIconName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getModeCompat](get-mode-compat.md) | `open fun getModeCompat(): `[`VehicleMode`](../-vehicle-mode/index.md)`!` |
| [getRemoteDarkIconName](get-remote-dark-icon-name.md) | `open fun getRemoteDarkIconName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getRemoteIconIsTemplate](get-remote-icon-is-template.md) | `open fun getRemoteIconIsTemplate(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [getRemoteIconName](get-remote-icon-name.md) | `open fun getRemoteIconName(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [setAlternativeText](set-alternative-text.md) | `open fun setAlternativeText(alternativeText: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setColor](set-color.md) | `open fun setColor(color: `[`ServiceColor`](../-service-color/index.md)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setDescription](set-description.md) | `open fun setDescription(description: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setId](set-id.md) | `open fun setId(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setLocalIconName](set-local-icon-name.md) | `open fun setLocalIconName(localIconName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRemoteDarkIconName](set-remote-dark-icon-name.md) | `open fun setRemoteDarkIconName(remoteDarkIconName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRemoteIconIsTemplate](set-remote-icon-is-template.md) | `open fun setRemoteIconIsTemplate(remoteIconIsTemplate: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRemoteIconName](set-remote-icon-name.md) | `open fun setRemoteIconName(remoteIconName: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [writeToParcel](write-to-parcel.md) | `open fun writeToParcel(dest: Parcel!, flags: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Extension Functions

| Name | Summary |
|---|---|
| [toEntity](../../com.skedgo.tripkit.data.database.stops/to-entity.md) | `fun `[`ModeInfo`](./index.md)`.toEntity(): `[`ModeInfoEntity`](../../com.skedgo.tripkit.data.database.locations.bikepods/-mode-info-entity/index.md) |
