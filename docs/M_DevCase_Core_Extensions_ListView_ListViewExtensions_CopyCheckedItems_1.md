# ListViewExtensions.CopyCheckedItems Method (ListView, String)
 

Copies all the text contained in the current checked items of ListView to the clipboard.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListView">DevCase.Core.Extensions.ListView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void CopyCheckedItems(
	this ListView sender,
	string separator
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub CopyCheckedItems ( 
	sender As ListView,
	separator As String
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As ListView
Dim separator As String

sender.CopyCheckedItems(separator)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void CopyCheckedItems(
	ListView^ sender, 
	String^ separator
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CopyCheckedItems : 
        sender : ListView * 
        separator : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.ListView<br />The source ListView.</dd><dt>separator</dt><dd>Type: System.String<br />The string used to separate the text of the subitems.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_ListView_ListViewExtensions_CopyCheckedItems">CopyCheckedItems Overload</a><br /><a href="N_DevCase_Core_Extensions_ListView">DevCase.Core.Extensions.ListView Namespace</a><br />