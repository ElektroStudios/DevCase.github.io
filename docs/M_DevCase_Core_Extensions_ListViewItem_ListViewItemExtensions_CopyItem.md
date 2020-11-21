# ListViewItemExtensions.CopyItem Method (ListViewItem)
 

Copies all the text contained in the specified ListViewItem to the clipboard.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListViewItem">DevCase.Core.Extensions.ListViewItem</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void CopyItem(
	this ListViewItem item
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub CopyItem ( 
	item As ListViewItem
)
```

**VB Usage**<br />
``` VB Usage
Dim item As ListViewItem

item.CopyItem()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void CopyItem(
	ListViewItem^ item
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CopyItem : 
        item : ListViewItem -> unit 

```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: System.Windows.Forms.ListViewItem<br />The item to copy.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListViewItem. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListViewItem_ListViewItemExtensions">ListViewItemExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_ListViewItem_ListViewItemExtensions_CopyItem">CopyItem Overload</a><br /><a href="N_DevCase_Core_Extensions_ListViewItem">DevCase.Core.Extensions.ListViewItem Namespace</a><br />