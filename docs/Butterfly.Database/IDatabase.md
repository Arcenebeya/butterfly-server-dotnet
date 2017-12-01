# IDatabase interface

```csharp
public interface IDatabase
```

## Members

| name | description |
| --- | --- |
| [ConnectionString](IDatabase/ConnectionString.md) { get; } |  |
| [Tables](IDatabase/Tables.md) { get; } |  |
| [ApplyDefaultValues](IDatabase/ApplyDefaultValues.md)(…) |  |
| [BeginTransaction](IDatabase/BeginTransaction.md)() |  |
| [CreateFromResourceFileAsync](IDatabase/CreateFromResourceFileAsync.md)(…) |  |
| [CreateFromTextAsync](IDatabase/CreateFromTextAsync.md)(…) |  |
| [DeleteAndCommitAsync](IDatabase/DeleteAndCommitAsync.md)(…) |  |
| [GetInitialDataEventsAsync](IDatabase/GetInitialDataEventsAsync.md)(…) |  |
| [GetInitialDataEventTransactionAsync](IDatabase/GetInitialDataEventTransactionAsync.md)(…) |  |
| [InsertAndCommitAsync](IDatabase/InsertAndCommitAsync.md)(…) |  |
| [OnNewCommittedTransaction](IDatabase/OnNewCommittedTransaction.md)(…) |  (2 methods) |
| [OnNewUncommittedTransaction](IDatabase/OnNewUncommittedTransaction.md)(…) |  (2 methods) |
| [SelectRowAsync](IDatabase/SelectRowAsync.md)(…) |  |
| [SelectRowsAsync](IDatabase/SelectRowsAsync.md)(…) |  (3 methods) |
| [SelectValue&lt;T&gt;](IDatabase/SelectValue.md)(…) |  |
| [SetDefaultValue](IDatabase/SetDefaultValue.md)(…) |  |
| [UpdateAndCommitAsync](IDatabase/UpdateAndCommitAsync.md)(…) |  |

## See Also

* namespace [Butterfly.Database](../Butterfly.Database.md)

<!-- DO NOT EDIT: generated by xmldocmd for Butterfly.Database.dll -->