SqlTable&lt;TEntity>.UpdateRange Method (TEntity[])
===================================================
Executes UPDATE commands for the specified *entities*, using the default [ConcurrencyConflictPolicy][1].

**Namespace:** [DbExtensions][2]  
**Assembly:** DbExtensions (in DbExtensions.dll)

Syntax
------

```csharp
public void UpdateRange(
	params TEntity[] entities
)
```

#### Parameters

##### *entities*
Type: [TEntity][3][]  
The entities whose UPDATE commands are to be executed.


See Also
--------

#### Reference
[SqlTable&lt;TEntity> Class][3]  
[DbExtensions Namespace][2]  

[1]: ../ConcurrencyConflictPolicy/README.md
[2]: ../README.md
[3]: README.md