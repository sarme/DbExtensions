Extensions.CreateCommand Method (DbProviderFactory, String)
===========================================================
Creates and returns a [DbCommand][1] object whose [CommandText][2] property is initialized with the *commandText* parameter.

**Namespace:** [DbExtensions][3]  
**Assembly:** DbExtensions (in DbExtensions.dll)

Syntax
------

```csharp
public static DbCommand CreateCommand(
	this DbProviderFactory factory,
	string commandText
)
```

#### Parameters

##### *factory*
Type: [System.Data.Common.DbProviderFactory][4]  
The provider factory used to create the command.

##### *commandText*
Type: [System.String][5]  
The command text.

#### Return Value
Type: [DbCommand][1]  
 A new [DbCommand][1] object whose [CommandText][2] property is initialized with the *commandText* parameter. 
#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type [DbProviderFactory][4]. When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)][6] or [Extension Methods (C# Programming Guide)][7].

See Also
--------

#### Reference
[Extensions Class][8]  
[DbExtensions Namespace][3]  

[1]: http://msdn.microsoft.com/en-us/library/852d01k6
[2]: http://msdn.microsoft.com/en-us/library/9d2hk99t
[3]: ../README.md
[4]: http://msdn.microsoft.com/en-us/library/c6c4a26c
[5]: http://msdn.microsoft.com/en-us/library/s1wwdcbf
[6]: http://msdn.microsoft.com/en-us/library/bb384936.aspx
[7]: http://msdn.microsoft.com/en-us/library/bb383977.aspx
[8]: README.md