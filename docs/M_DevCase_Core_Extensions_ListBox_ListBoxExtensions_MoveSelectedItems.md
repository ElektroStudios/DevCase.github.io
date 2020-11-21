# ListBoxExtensions.MoveSelectedItems Method 
 

Moves up or down the selected items of the ListBox.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void MoveSelectedItems(
	this ListBox sender,
	RowMoveDirection direction
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub MoveSelectedItems ( 
	sender As ListBox,
	direction As RowMoveDirection
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As ListBox
Dim direction As RowMoveDirection

sender.MoveSelectedItems(direction)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void MoveSelectedItems(
	ListBox^ sender, 
	RowMoveDirection direction
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member MoveSelectedItems : 
        sender : ListBox * 
        direction : RowMoveDirection -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.ListBox<br />The source ListBox.</dd><dt>direction</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_RowMoveDirection">DevCase.Core.Application.UserInterface.RowMoveDirection</a><br />The item move direction.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListBox. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox Namespace</a><br />