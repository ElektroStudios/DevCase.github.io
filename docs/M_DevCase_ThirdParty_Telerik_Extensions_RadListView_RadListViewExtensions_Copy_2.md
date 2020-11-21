# RadListViewExtensions.Copy Method (RadListView, String)
 

Copies all the text contained in the items of RadListView to the clipboard.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListView">DevCase.ThirdParty.Telerik.Extensions.RadListView</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void Copy(
	this RadListView sender,
	string separator
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub Copy ( 
	sender As RadListView,
	separator As String
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RadListView
Dim separator As String

sender.Copy(separator)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void Copy(
	RadListView^ sender, 
	String^ separator
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member Copy : 
        sender : RadListView * 
        separator : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: RadListView<br />The source RadListView.</dd><dt>separator</dt><dd>Type: System.String<br />The string used to separate the text of the subitems.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RadListView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_RadListView_RadListViewExtensions">RadListViewExtensions Class</a><br /><a href="Overload_DevCase_ThirdParty_Telerik_Extensions_RadListView_RadListViewExtensions_Copy">Copy Overload</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListView">DevCase.ThirdParty.Telerik.Extensions.RadListView Namespace</a><br />