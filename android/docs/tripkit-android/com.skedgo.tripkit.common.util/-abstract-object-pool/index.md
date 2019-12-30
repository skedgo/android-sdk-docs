[tripkit-android](../../index.md) / [com.skedgo.tripkit.common.util](../index.md) / [AbstractObjectPool](./index.md)

# AbstractObjectPool

`abstract class AbstractObjectPool<T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`!>`

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `AbstractObjectPool()` |

### Functions

| Name | Summary |
|---|---|
| [newObject](new-object.md) | By default, attempts to invoke a no-arg constructor on class T. `open fun newObject(): T` |
| [onRecycle](on-recycle.md) | Gives subclasses the chance to perform additional operations on an object *before* it is recycled.`open fun onRecycle(obj: T): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [retrieve](retrieve.md) | `fun retrieve(): T` |
| [save](save.md) | `fun save(obj: T): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| Name | Summary |
|---|---|
| [StringBuilderPool](../-string-builder-pool/index.md) | `open class StringBuilderPool : `[`AbstractObjectPool`](./index.md)`<`[`StringBuilder`](https://docs.oracle.com/javase/7/docs/api/java/lang/StringBuilder.html)`!>` |
