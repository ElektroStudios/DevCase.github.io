# ListBoxExtensions.SetSelectedNoJump Method (ListBox, String, ListBoxItemSelectionState)
 

Selects or unselects the specified item in ListBox without scrolling to its item position.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void SetSelectedNoJump(
	this ListBox sender,
	string itemText,
	ListBoxItemSelectionState selection
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub SetSelectedNoJump ( 
	sender As ListBox,
	itemText As String,
	selection As ListBoxItemSelectionState
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As ListBox
Dim itemText As String
Dim selection As ListBoxItemSelectionState

sender.SetSelectedNoJump(itemText, 
	selection)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void SetSelectedNoJump(
	ListBox^ sender, 
	String^ itemText, 
	ListBoxItemSelectionState selection
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetSelectedNoJump : 
        sender : ListBox * 
        itemText : string * 
        selection : ListBoxItemSelectionState -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.ListBox<br />The source ListBox.</dd><dt>itemText</dt><dd>Type: System.String<br />The text of the item to select.</dd><dt>selection</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_ListBoxItemSelectionState">DevCase.Core.Application.UserInterface.ListBoxItemSelectionState</a><br />A value indicating whether items should be selected, or unselected.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListBox. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
ListBox1.SetSelectedNoJump("Item1", ListBoxItemSelectionState.Select)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListBox_ListBoxExtensions">ListBoxExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_ListBox_ListBoxExtensions_SetSelectedNoJump">SetSelectedNoJump Overload</a><br /><a href="N_DevCase_Core_Extensions_ListBox">DevCase.Core.Extensions.ListBox Namespace</a><br />