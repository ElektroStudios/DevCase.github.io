# RadListControlExtensions.CopyItem Method 
 

Copies the text of the specified item in the RadListControl to the clipboard.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListControl">DevCase.ThirdParty.Telerik.Extensions.RadListControl</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void CopyItem(
	this RadListControl sender,
	int itemIndex
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub CopyItem ( 
	sender As RadListControl,
	itemIndex As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RadListControl
Dim itemIndex As Integer

sender.CopyItem(itemIndex)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void CopyItem(
	RadListControl^ sender, 
	int itemIndex
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CopyItem : 
        sender : RadListControl * 
        itemIndex : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: RadListControl<br />The source RadListControl.</dd><dt>itemIndex</dt><dd>Type: System.Int32<br />The index of the item to copy.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RadListControl. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_RadListControl_RadListControlExtensions">RadListControlExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListControl">DevCase.ThirdParty.Telerik.Extensions.RadListControl Namespace</a><br />