# RadListViewExtensions.CopyItem Method (RadListView, Int32, String, Int32)
 

Copies all the text contained in the specified ListViewDataItem to the clipboard.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListView">DevCase.ThirdParty.Telerik.Extensions.RadListView</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void CopyItem(
	this RadListView sender,
	int itemIndex,
	string separator,
	int subItemIndex
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub CopyItem ( 
	sender As RadListView,
	itemIndex As Integer,
	separator As String,
	subItemIndex As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RadListView
Dim itemIndex As Integer
Dim separator As String
Dim subItemIndex As Integer

sender.CopyItem(itemIndex, separator, 
	subItemIndex)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void CopyItem(
	RadListView^ sender, 
	int itemIndex, 
	String^ separator, 
	int subItemIndex
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CopyItem : 
        sender : RadListView * 
        itemIndex : int * 
        separator : string * 
        subItemIndex : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: RadListView<br />The source RadListView.</dd><dt>itemIndex</dt><dd>Type: System.Int32<br />The index of the item to copy.</dd><dt>separator</dt><dd>Type: System.String<br />The string used to separate the text of the subitems.</dd><dt>subItemIndex</dt><dd>Type: System.Int32<br />The index of the ListViewDataItem to copy. 

 If *subItemIndex* is `-1`, all subitems are copied.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RadListView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_RadListView_RadListViewExtensions">RadListViewExtensions Class</a><br /><a href="Overload_DevCase_ThirdParty_Telerik_Extensions_RadListView_RadListViewExtensions_CopyItem">CopyItem Overload</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListView">DevCase.ThirdParty.Telerik.Extensions.RadListView Namespace</a><br />