# ListViewItemExtensions.CopyItems Method (ListViewItem[], String, Int32)
 

Copies all the text contained in the specified items of ListView to the clipboard.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListViewItem">DevCase.Core.Extensions.ListViewItem</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void CopyItems(
	this ListViewItem[] items,
	string separator,
	int subItemIndex
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub CopyItems ( 
	items As ListViewItem(),
	separator As String,
	subItemIndex As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim items As ListViewItem()
Dim separator As String
Dim subItemIndex As Integer

items.CopyItems(separator, subItemIndex)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void CopyItems(
	array<ListViewItem^>^ items, 
	String^ separator, 
	int subItemIndex
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CopyItems : 
        items : ListViewItem[] * 
        separator : string * 
        subItemIndex : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>items</dt><dd>Type: System.Windows.Forms.ListViewItem[]<br />The items to copy.</dd><dt>separator</dt><dd>Type: System.String<br />The string used to separate the text of the subitems.</dd><dt>subItemIndex</dt><dd>Type: System.Int32<br />The index of the ListViewItem.ListViewSubItem to copy. 

 If *subItemIndex* is `-1`, all subitems are copied.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListViewItem_ListViewItemExtensions">ListViewItemExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_ListViewItem_ListViewItemExtensions_CopyItems">CopyItems Overload</a><br /><a href="N_DevCase_Core_Extensions_ListViewItem">DevCase.Core.Extensions.ListViewItem Namespace</a><br />