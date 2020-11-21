# DataGridViewExtensions.MoveSelectedRows Method (DataGridView, RowMoveDirection)
 

Moves up or down the selected rows of the DataGridView.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DataGridView">DevCase.Core.Extensions.DataGridView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void MoveSelectedRows(
	this DataGridView sender,
	RowMoveDirection direction
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub MoveSelectedRows ( 
	sender As DataGridView,
	direction As RowMoveDirection
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As DataGridView
Dim direction As RowMoveDirection

sender.MoveSelectedRows(direction)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void MoveSelectedRows(
	DataGridView^ sender, 
	RowMoveDirection direction
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member MoveSelectedRows : 
        sender : DataGridView * 
        direction : RowMoveDirection -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.DataGridView<br />The source DataGridView.</dd><dt>direction</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_RowMoveDirection">DevCase.Core.Application.UserInterface.RowMoveDirection</a><br />The row-move direction.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DataGridView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DataGridView_DataGridViewExtensions">DataGridViewExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_DataGridView_DataGridViewExtensions_MoveSelectedRows">MoveSelectedRows Overload</a><br /><a href="N_DevCase_Core_Extensions_DataGridView">DevCase.Core.Extensions.DataGridView Namespace</a><br />