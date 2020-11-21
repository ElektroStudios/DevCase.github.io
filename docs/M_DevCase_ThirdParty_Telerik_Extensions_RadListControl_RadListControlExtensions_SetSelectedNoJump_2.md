# RadListControlExtensions.SetSelectedNoJump Method (RadListControl, String, RadListItemSelectionState)
 

Selects or unselects the specified item in RadListControl without scrolling to its item position.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListControl">DevCase.ThirdParty.Telerik.Extensions.RadListControl</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void SetSelectedNoJump(
	this RadListControl sender,
	string itemText,
	RadListItemSelectionState selection
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub SetSelectedNoJump ( 
	sender As RadListControl,
	itemText As String,
	selection As RadListItemSelectionState
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RadListControl
Dim itemText As String
Dim selection As RadListItemSelectionState

sender.SetSelectedNoJump(itemText, 
	selection)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void SetSelectedNoJump(
	RadListControl^ sender, 
	String^ itemText, 
	RadListItemSelectionState selection
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetSelectedNoJump : 
        sender : RadListControl * 
        itemText : string * 
        selection : RadListItemSelectionState -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: RadListControl<br />The source RadListControl.</dd><dt>itemText</dt><dd>Type: System.String<br />The text of the item to select.</dd><dt>selection</dt><dd>Type: <a href="T_DevCase_ThirdParty_Telerik_RadListItemSelectionState">DevCase.ThirdParty.Telerik.RadListItemSelectionState</a><br />A value indicating whether items should be selected, or unselected.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RadListControl. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
RadListControl1.SetSelectedNoJump("Item1", RadListItemSelectionState.Select)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_RadListControl_RadListControlExtensions">RadListControlExtensions Class</a><br /><a href="Overload_DevCase_ThirdParty_Telerik_Extensions_RadListControl_RadListControlExtensions_SetSelectedNoJump">SetSelectedNoJump Overload</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListControl">DevCase.ThirdParty.Telerik.Extensions.RadListControl Namespace</a><br />