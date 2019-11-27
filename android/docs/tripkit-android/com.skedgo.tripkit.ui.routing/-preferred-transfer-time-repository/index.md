[tripkit-android](../../index.md) / [com.skedgo.tripkit.ui.routing](../index.md) / [PreferredTransferTimeRepository](./index.md)

# PreferredTransferTimeRepository

`interface PreferredTransferTimeRepository`

### Functions

| Name | Summary |
|---|---|
| [getPreferredTransferTime](get-preferred-transfer-time.md) | `abstract fun getPreferredTransferTime(defaultIfEmpty: () -> Minutes = { Minutes.THREE }): Observable<Minutes>` |
| [putPreferredTransferTime](put-preferred-transfer-time.md) | `abstract fun putPreferredTransferTime(preferredTransferTime: Minutes): Completable` |
| [whenPreferredTransferTimeChanges](when-preferred-transfer-time-changes.md) | Emits when preferred transfer time has changed.`abstract fun whenPreferredTransferTimeChanges(): Observable<Minutes>` |
