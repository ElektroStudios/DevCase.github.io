# RadListViewExtensions.MoveSelectedItems Method 
 

Moves up or down the selected items of the RadListView.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListView">DevCase.ThirdParty.Telerik.Extensions.RadListView</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void MoveSelectedItems(
	this RadListView sender,
	RowMoveDirection direction
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub MoveSelectedItems ( 
	sender As RadListView,
	direction As RowMoveDirection
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RadListView
Dim direction As RowMoveDirection

sender.MoveSelectedItems(direction)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void MoveSelectedItems(
	RadListView^ sender, 
	RowMoveDirection direction
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member MoveSelectedItems : 
        sender : RadListView * 
        direction : RowMoveDirection -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: RadListView<br />The source RadListView.</dd><dt>direction</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_RowMoveDirection">DevCase.Core.Application.UserInterface.RowMoveDirection</a><br />The row-move direction.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RadListView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_RadListView_RadListViewExtensions">RadListViewExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListView">DevCase.ThirdParty.Telerik.Extensions.RadListView Namespace</a><br />