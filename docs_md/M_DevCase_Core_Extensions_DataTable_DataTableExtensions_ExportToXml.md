# DataTableExtensions.ExportToXml Method 
 

Exports the source DataTable to `Xml` format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DataTable">DevCase.Core.Extensions.DataTable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ExportToXml(
	this DataTable sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ExportToXml ( 
	sender As DataTable
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As DataTable
Dim returnValue As String

returnValue = sender.ExportToXml()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ExportToXml(
	DataTable^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ExportToXml : 
        sender : DataTable -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Data.DataTable<br />The source DataTable.</dd></dl>

#### Return Value
Type: String<br />The resulting `Xml` string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DataTable. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dt As New DataTable()
dt.Columns.Add("Name", GetType(String))
dt.Columns.Add("Date", GetType(Date))
dt.Rows.Add("Elektro", Date.Parse("01-01-2016"))

Dim xml As String = dt.ExportToXml()
Console.WriteLine(xml)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DataTable_DataTableExtensions">DataTableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DataTable">DevCase.Core.Extensions.DataTable Namespace</a><br />