# DbConnectionExtensions.CreateCommand Method 
 

Creates and returns a DbCommand object associated with the current connection.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DbConnection">DevCase.Core.Extensions.DbConnection</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static DbCommand CreateCommand(
	this DbConnection connection,
	string commandTextFormat,
	params Object[] parameters
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function CreateCommand ( 
	connection As DbConnection,
	commandTextFormat As String,
	ParamArray parameters As Object()
) As DbCommand
```

**VB Usage**<br />
``` VB Usage
Dim connection As DbConnection
Dim commandTextFormat As String
Dim parameters As Object()
Dim returnValue As DbCommand

returnValue = connection.CreateCommand(commandTextFormat, 
	parameters)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static DbCommand^ CreateCommand(
	DbConnection^ connection, 
	String^ commandTextFormat, 
	... array<Object^>^ parameters
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CreateCommand : 
        connection : DbConnection * 
        commandTextFormat : string * 
        parameters : Object[] -> DbCommand 

```


#### Parameters
&nbsp;<dl><dt>connection</dt><dd>Type: System.Data.Common.DbConnection<br />The source DbConnection.</dd><dt>commandTextFormat</dt><dd>Type: System.String<br />The format of the text command to run against the data source.</dd><dt>parameters</dt><dd>Type: System.Object[]<br />The names of the parameters.</dd></dl>

#### Return Value
Type: DbCommand<br />The resulting DbCommand object.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DbConnection. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim connection As DbConnection = ...
Dim command As DbCommand = connection.CreateCommand("SELECT {0}", "Parameter0")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DbConnection_DbConnectionExtensions">DbConnectionExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DbConnection">DevCase.Core.Extensions.DbConnection Namespace</a><br />