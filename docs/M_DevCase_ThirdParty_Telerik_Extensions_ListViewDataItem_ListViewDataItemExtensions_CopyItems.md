# ListViewDataItemExtensions.CopyItems Method (ListViewDataItem[])
 

Copies all the text contained in the specified items of RadListView to the clipboard.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_ListViewDataItem">DevCase.ThirdParty.Telerik.Extensions.ListViewDataItem</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void CopyItems(
	this ListViewDataItem[] items
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub CopyItems ( 
	items As ListViewDataItem()
)
```

**VB Usage**<br />
``` VB Usage
Dim items As ListViewDataItem()

items.CopyItems()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void CopyItems(
	array<ListViewDataItem^>^ items
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CopyItems : 
        items : ListViewDataItem[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>items</dt><dd>Type: ListViewDataItem[]<br />The items to copy.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_ListViewDataItem_ListViewDataItemExtensions">ListViewDataItemExtensions Class</a><br /><a href="Overload_DevCase_ThirdParty_Telerik_Extensions_ListViewDataItem_ListViewDataItemExtensions_CopyItems">CopyItems Overload</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_ListViewDataItem">DevCase.ThirdParty.Telerik.Extensions.ListViewDataItem Namespace</a><br />