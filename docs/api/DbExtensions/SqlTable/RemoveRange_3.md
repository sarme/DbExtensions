SqlTable.RemoveRange Method (Object[], ConcurrencyConflictPolicy)
=================================================================
Executes DELETE commands for the specified *entities*, using the provided *conflictPolicy*.

**Namespace:** [DbExtensions][1]  
**Assembly:** DbExtensions (in DbExtensions.dll)

Syntax
------

```csharp
public void RemoveRange(
	Object[] entities,
	ConcurrencyConflictPolicy conflictPolicy
)
```

#### Parameters

##### *entities*
Type: [System.Object][2][]  
The entities whose DELETE commands are to be executed.

##### *conflictPolicy*
Type: [DbExtensions.ConcurrencyConflictPolicy][3]  
 The [ConcurrencyConflictPolicy][3] that specifies what columns to check for in the DELETE predicate, and how to validate the affected records value.


See Also
--------

#### Reference
[SqlTable Class][4]  
[DbExtensions Namespace][1]  

[1]: ../README.md
[2]: http://msdn.microsoft.com/en-us/library/e5kfa45b
[3]: ../ConcurrencyConflictPolicy/README.md
[4]: README.md