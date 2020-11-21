# ListViewExtensions.MoveSelectedItems Method (ListView, RowMoveDirection, IEnumerable(Int32))
 

Moves up or down the selected items of the ListView.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListView">DevCase.Core.Extensions.ListView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void MoveSelectedItems(
	this ListView sender,
	RowMoveDirection direction,
	IEnumerable<int> preserveSubitemIndices
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub MoveSelectedItems ( 
	sender As ListView,
	direction As RowMoveDirection,
	preserveSubitemIndices As IEnumerable(Of Integer)
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As ListView
Dim direction As RowMoveDirection
Dim preserveSubitemIndices As IEnumerable(Of Integer)

sender.MoveSelectedItems(direction, 
	preserveSubitemIndices)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void MoveSelectedItems(
	ListView^ sender, 
	RowMoveDirection direction, 
	IEnumerable<int>^ preserveSubitemIndices
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member MoveSelectedItems : 
        sender : ListView * 
        direction : RowMoveDirection * 
        preserveSubitemIndices : IEnumerable<int> -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.ListView<br />The source ListView.</dd><dt>direction</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_RowMoveDirection">DevCase.Core.Application.UserInterface.RowMoveDirection</a><br />The row-move direction.</dd><dt>preserveSubitemIndices</dt><dd>Type: System.Collections.Generic.IEnumerable(Int32)<br />A sequence of subitem indices to preserve their values when moving the items.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_ListView_ListViewExtensions_MoveSelectedItems">MoveSelectedItems Overload</a><br /><a href="N_DevCase_Core_Extensions_ListView">DevCase.Core.Extensions.ListView Namespace</a><br />