# RadListViewExtensions.CopyItems Method (RadListView, Int32[], String)
 

Copies all the text contained in the specified items of RadListView to the clipboard.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListView">DevCase.ThirdParty.Telerik.Extensions.RadListView</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void CopyItems(
	this RadListView sender,
	int[] indices,
	string separator
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub CopyItems ( 
	sender As RadListView,
	indices As Integer(),
	separator As String
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RadListView
Dim indices As Integer()
Dim separator As String

sender.CopyItems(indices, separator)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void CopyItems(
	RadListView^ sender, 
	array<int>^ indices, 
	String^ separator
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CopyItems : 
        sender : RadListView * 
        indices : int[] * 
        separator : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: RadListView<br />The source RadListView.</dd><dt>indices</dt><dd>Type: System.Int32[]<br />The indices of the items to copy.</dd><dt>separator</dt><dd>Type: System.String<br />The string used to separate the text of the subitems.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RadListView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_RadListView_RadListViewExtensions">RadListViewExtensions Class</a><br /><a href="Overload_DevCase_ThirdParty_Telerik_Extensions_RadListView_RadListViewExtensions_CopyItems">CopyItems Overload</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListView">DevCase.ThirdParty.Telerik.Extensions.RadListView Namespace</a><br />