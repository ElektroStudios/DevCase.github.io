# DataTableExtensions.ExportToCSV Method 
 

Exports the source DataTable to `CSV` table format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DataTable">DevCase.Core.Extensions.DataTable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ExportToCSV(
	this DataTable sender,
	string defaultValueIfEmpty = ""
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ExportToCSV ( 
	sender As DataTable,
	Optional defaultValueIfEmpty As String = ""
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As DataTable
Dim defaultValueIfEmpty As String
Dim returnValue As String

returnValue = sender.ExportToCSV(defaultValueIfEmpty)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ExportToCSV(
	DataTable^ sender, 
	String^ defaultValueIfEmpty = L""
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ExportToCSV : 
        sender : DataTable * 
        ?defaultValueIfEmpty : string 
(* Defaults:
        let _defaultValueIfEmpty = defaultArg defaultValueIfEmpty ""
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Data.DataTable<br />The source DataTable.</dd><dt>defaultValueIfEmpty (Optional)</dt><dd>Type: System.String<br />A default value to write in a `CSV` field if the corresponding Item(DataColumn) value is a null reference (`Nothing` in Visual Basic).</dd></dl>

#### Return Value
Type: String<br />The resulting `CSV` table string.

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

Dim csv As String = dt.ExportToCSV(defaultValueIfEmpty:="N/A")
Console.WriteLine(csv)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DataTable_DataTableExtensions">DataTableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DataTable">DevCase.Core.Extensions.DataTable Namespace</a><br />