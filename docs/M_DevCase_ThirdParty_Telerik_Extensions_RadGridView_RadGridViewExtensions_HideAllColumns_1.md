# RadGridViewExtensions.HideAllColumns Method (RadGridView, Int32[])
 

Hides all the columns of the RadGridView, except the specified columns.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_RadGridView">DevCase.ThirdParty.Telerik.Extensions.RadGridView</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void HideAllColumns(
	this RadGridView sender,
	int[] excludeColumnIndices
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub HideAllColumns ( 
	sender As RadGridView,
	excludeColumnIndices As Integer()
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RadGridView
Dim excludeColumnIndices As Integer()

sender.HideAllColumns(excludeColumnIndices)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void HideAllColumns(
	RadGridView^ sender, 
	array<int>^ excludeColumnIndices
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member HideAllColumns : 
        sender : RadGridView * 
        excludeColumnIndices : int[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: RadGridView<br />The source RadGridView.</dd><dt>excludeColumnIndices</dt><dd>Type: System.Int32[]<br />The indices of the columns to exclude.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RadGridView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_RadGridView_RadGridViewExtensions">RadGridViewExtensions Class</a><br /><a href="Overload_DevCase_ThirdParty_Telerik_Extensions_RadGridView_RadGridViewExtensions_HideAllColumns">HideAllColumns Overload</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_RadGridView">DevCase.ThirdParty.Telerik.Extensions.RadGridView Namespace</a><br />