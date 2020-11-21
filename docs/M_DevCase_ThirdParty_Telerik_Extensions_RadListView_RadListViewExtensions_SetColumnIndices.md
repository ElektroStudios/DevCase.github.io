# RadListViewExtensions.SetColumnIndices Method 
 

Indices the rows of a column of the RadListView.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListView">DevCase.ThirdParty.Telerik.Extensions.RadListView</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void SetColumnIndices(
	this RadListView sender,
	int columnIndex,
	int startingIndex = 1
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub SetColumnIndices ( 
	sender As RadListView,
	columnIndex As Integer,
	Optional startingIndex As Integer = 1
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As RadListView
Dim columnIndex As Integer
Dim startingIndex As Integer

sender.SetColumnIndices(columnIndex, 
	startingIndex)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void SetColumnIndices(
	RadListView^ sender, 
	int columnIndex, 
	int startingIndex = 1
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member SetColumnIndices : 
        sender : RadListView * 
        columnIndex : int * 
        ?startingIndex : int 
(* Defaults:
        let _startingIndex = defaultArg startingIndex 1
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: RadListView<br />The source RadListView.</dd><dt>columnIndex</dt><dd>Type: System.Int32<br />The column index.</dd><dt>startingIndex (Optional)</dt><dd>Type: System.Int32<br />The starting index number. 

 Default value is `1`.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RadListView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Telerik_Extensions_RadListView_RadListViewExtensions">RadListViewExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Telerik_Extensions_RadListView">DevCase.ThirdParty.Telerik.Extensions.RadListView Namespace</a><br />