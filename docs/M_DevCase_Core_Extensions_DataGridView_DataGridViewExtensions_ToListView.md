# DataGridViewExtensions.ToListView Method 
 

Converts the source DataGridView to a ListView.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DataGridView">DevCase.Core.Extensions.DataGridView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static ListView ToListView(
	this DataGridView sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToListView ( 
	sender As DataGridView
) As ListView
```

**VB Usage**<br />
``` VB Usage
Dim sender As DataGridView
Dim returnValue As ListView

returnValue = sender.ToListView()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static ListView^ ToListView(
	DataGridView^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToListView : 
        sender : DataGridView -> ListView 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.DataGridView<br />The source DataGridView.</dd></dl>

#### Return Value
Type: ListView<br />The resulting ListView.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DataGridView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dgv As New DataGridView
With dgv
    .Columns.Add(columnName:="Column1", headerText:="Column1")
    .Columns.Add(columnName:="Column2", headerText:="Column2")
    .Columns.Add(columnName:="Column3", headerText:="Column3")

    .Rows.Add({"Cell A1", "Cell A2", "Cell A3"})
    .Rows.Add({"Cell B1", "Cell B2", "Cell B3"})
    .Rows.Add({"Cell C1", "Cell C2", "Cell C3"})
End With

Dim lv As ListView = dgv.ToListView()
lv.View = View.Details
lv.Dock = DockStyle.Fill

Me.Controls.Add(lv)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DataGridView_DataGridViewExtensions">DataGridViewExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DataGridView">DevCase.Core.Extensions.DataGridView Namespace</a><br />