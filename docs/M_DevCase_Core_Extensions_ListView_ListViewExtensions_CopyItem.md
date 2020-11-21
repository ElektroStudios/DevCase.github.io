# ListViewExtensions.CopyItem Method (ListView, Int32)
 

Copies all the text contained in the specified ListViewItem to the clipboard.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListView">DevCase.Core.Extensions.ListView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void CopyItem(
	this ListView sender,
	int itemIndex
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub CopyItem ( 
	sender As ListView,
	itemIndex As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As ListView
Dim itemIndex As Integer

sender.CopyItem(itemIndex)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void CopyItem(
	ListView^ sender, 
	int itemIndex
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CopyItem : 
        sender : ListView * 
        itemIndex : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.ListView<br />The source ListView.</dd><dt>itemIndex</dt><dd>Type: System.Int32<br />The index of the item to copy.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyItem">CopyItem Overload</a><br /><a href="N_DevCase_Core_Extensions_ListView">DevCase.Core.Extensions.ListView Namespace</a><br />