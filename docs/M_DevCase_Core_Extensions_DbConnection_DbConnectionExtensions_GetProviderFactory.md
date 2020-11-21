# DbConnectionExtensions.GetProviderFactory Method 
 

Gets the DbProviderFactory for the source DbConnection.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DbConnection">DevCase.Core.Extensions.DbConnection</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static DbProviderFactory GetProviderFactory(
	this DbConnection connection
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetProviderFactory ( 
	connection As DbConnection
) As DbProviderFactory
```

**VB Usage**<br />
``` VB Usage
Dim connection As DbConnection
Dim returnValue As DbProviderFactory

returnValue = connection.GetProviderFactory()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static DbProviderFactory^ GetProviderFactory(
	DbConnection^ connection
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetProviderFactory : 
        connection : DbConnection -> DbProviderFactory 

```


#### Parameters
&nbsp;<dl><dt>connection</dt><dd>Type: System.Data.Common.DbConnection<br />The source DbConnection.</dd></dl>

#### Return Value
Type: DbProviderFactory<br />The resulting DbProviderFactory.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DbConnection. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DbConnection_DbConnectionExtensions">DbConnectionExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DbConnection">DevCase.Core.Extensions.DbConnection Namespace</a><br />