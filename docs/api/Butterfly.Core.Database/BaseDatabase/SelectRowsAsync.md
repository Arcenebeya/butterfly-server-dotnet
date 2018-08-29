# BaseDatabase.SelectRowsAsync method (1 of 2)

```csharp
public Task<Dictionary<string, object>[]> SelectRowsAsync(SelectStatement statement, object vars)
```

## See Also

* class [SelectStatement](../SelectStatement.md)
* class [BaseDatabase](../BaseDatabase.md)
* namespace [Butterfly.Core.Database](../../Butterfly.Core.md)

---

# BaseDatabase.SelectRowsAsync method (2 of 2)

Executes the SELECT statement and return the rows (the SELECT statement may contain vars like @name specified in *vars*)

```csharp
public Task<Dictionary<string, object>[]> SelectRowsAsync(string statementSql, object vars = null, 
    int overrideLimit = -1)
```

| parameter | description |
| --- | --- |
| selectStatement |  |
| vars |  |
| overrideLimit |  |

## See Also

* class [BaseDatabase](../BaseDatabase.md)
* namespace [Butterfly.Core.Database](../../Butterfly.Core.md)

<!-- DO NOT EDIT: generated by xmldocmd for Butterfly.Core.dll -->