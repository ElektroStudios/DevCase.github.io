# DataTableExtensions.ToDataGridView Method 
 

Converts the source DataTable to a DataGridView.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DataTable">DevCase.Core.Extensions.DataTable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static DataGridView ToDataGridView(
	this DataTable sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToDataGridView ( 
	sender As DataTable
) As DataGridView
```

**VB Usage**<br />
``` VB Usage
Dim sender As DataTable
Dim returnValue As DataGridView

returnValue = sender.ToDataGridView()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static DataGridView^ ToDataGridView(
	DataTable^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToDataGridView : 
        sender : DataTable -> DataGridView 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Data.DataTable<br />The source DataTable.</dd></dl>

#### Return Value
Type: DataGridView<br />The resulting DataGridView.

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

Dim dgv As DataGridView = dt.ToDataGridView()

Me.Controls.Add(dgv)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DataTable_DataTableExtensions">DataTableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DataTable">DevCase.Core.Extensions.DataTable Namespace</a><br />