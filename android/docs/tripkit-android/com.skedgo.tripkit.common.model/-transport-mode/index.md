[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.model](../index.md) / [TransportMode](./index.md)

# TransportMode

`open class TransportMode`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TransportMode()` |

### Properties

| Name | Summary |
|---|---|
| [ID_AIR](-i-d_-a-i-r.md) | `static val ID_AIR: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ID_BICYCLE](-i-d_-b-i-c-y-c-l-e.md) | `static val ID_BICYCLE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ID_CAR](-i-d_-c-a-r.md) | `static val ID_CAR: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ID_MOTORBIKE](-i-d_-m-o-t-o-r-b-i-k-e.md) | `static val ID_MOTORBIKE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ID_PUBLIC_TRANSPORT](-i-d_-p-u-b-l-i-c_-t-r-a-n-s-p-o-r-t.md) | `static val ID_PUBLIC_TRANSPORT: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ID_SCHOOL_BUS](-i-d_-s-c-h-o-o-l_-b-u-s.md) | `static val ID_SCHOOL_BUS: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ID_SHUFFLE](-i-d_-s-h-u-f-f-l-e.md) | `static val ID_SHUFFLE: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ID_SHUTTLE_BUS](-i-d_-s-h-u-t-t-l-e_-b-u-s.md) | FIXME: It seems we no longer need this id. Replacement seems to be 'pt_ltd_SCHOOLBUS'.`static val ID_SHUTTLE_BUS: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ID_TAXI](-i-d_-t-a-x-i.md) | `static val ID_TAXI: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ID_TNC](-i-d_-t-n-c.md) | `static val ID_TNC: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ID_WALK](-i-d_-w-a-l-k.md) | `static val ID_WALK: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [ID_WHEEL_CHAIR](-i-d_-w-h-e-e-l_-c-h-a-i-r.md) | `static val ID_WHEEL_CHAIR: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [MIDDLE_FIX_BIC](-m-i-d-d-l-e_-f-i-x_-b-i-c.md) | `static val MIDDLE_FIX_BIC: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [MIDDLE_FIX_CAR](-m-i-d-d-l-e_-f-i-x_-c-a-r.md) | `static val MIDDLE_FIX_CAR: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [equals](equals.md) | `open fun equals(other: `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`?): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [fromId](from-id.md) | `open static fun fromId(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`TransportMode`](./index.md)`!` |
| [getColor](get-color.md) | `open fun getColor(): `[`ServiceColor`](../../com.skedgo.tripkit.routing/-service-color/index.md)`?` |
| [getDarkIcon](get-dark-icon.md) | `open fun getDarkIcon(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [getIconId](get-icon-id.md) | `open fun getIconId(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getId](get-id.md) | `open fun getId(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getImplies](get-implies.md) | `open fun getImplies(): `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>?` |
| [getLocalIconResId](get-local-icon-res-id.md) | `open static fun getLocalIconResId(identifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?): `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [getTitle](get-title.md) | `open fun getTitle(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!` |
| [getURL](get-u-r-l.md) | `open fun getURL(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`?` |
| [isRequired](is-required.md) | `open fun isRequired(): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [setDarkIcon](set-dark-icon.md) | `open fun setDarkIcon(darkIcon: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setIconId](set-icon-id.md) | `open fun setIconId(iconId: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setId](set-id.md) | `open fun setId(id: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setImplies](set-implies.md) | `open fun setImplies(implies: `[`ArrayList`](https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!>!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setRequired](set-required.md) | `open fun setRequired(isRequired: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setTitle](set-title.md) | `open fun setTitle(title: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [setURL](set-u-r-l.md) | `open fun setURL(URL: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`!): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [toString](to-string.md) | `open fun toString(): `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
