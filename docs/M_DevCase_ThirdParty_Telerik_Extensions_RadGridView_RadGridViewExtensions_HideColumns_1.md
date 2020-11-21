# RadGridViewExtensions.HideColumns Method (RadGridView, String[])
 

Hides the specified columns of the RadGridView.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_RadGridView">DevCase.ThirdParty.Telerik.Extensions.RadGridView</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void HideColumns(
	this RadGridView sender,
	string[] columnNames
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub HideColumns ( 
	sender As RadGridView,
	columnNames As String()
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RadGridView
Dim columnNames As String()

sender.HideColumns(columnNames)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void HideColumns(
	RadGridView^ sender, 
	array<String^>^ columnNames
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member HideColumns : 
        sender : RadGridView * 
        columnNames : string[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: RadGridView<br />The source RadGridView.</dd><dt>columnNames</dt><dd>Type: System.String[]<br />The names of the columns to hide.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RadGridView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_RadGridView_RadGridViewExtensions">RadGridViewExtensions Class</a><br /><a href="Overload_DevCase_ThirdParty_Telerik_Extensions_RadGridView_RadGridViewExtensions_HideColumns">HideColumns Overload</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_RadGridView">DevCase.ThirdParty.Telerik.Extensions.RadGridView Namespace</a><br />