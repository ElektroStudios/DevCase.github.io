# DataGridViewExtensions.HideAllColumns Method (DataGridView, Int32[])
 

Hides all the columns of the DataGridView, except the specified columns.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DataGridView">DevCase.Core.Extensions.DataGridView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void HideAllColumns(
	this DataGridView sender,
	int[] excludeColumnIndices
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub HideAllColumns ( 
	sender As DataGridView,
	excludeColumnIndices As Integer()
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As DataGridView
Dim excludeColumnIndices As Integer()

sender.HideAllColumns(excludeColumnIndices)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void HideAllColumns(
	DataGridView^ sender, 
	array<int>^ excludeColumnIndices
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member HideAllColumns : 
        sender : DataGridView * 
        excludeColumnIndices : int[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.DataGridView<br />The source DataGridView.</dd><dt>excludeColumnIndices</dt><dd>Type: System.Int32[]<br />The indices of the columns to exclude.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DataGridView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DataGridView_DataGridViewExtensions">DataGridViewExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_DataGridView_DataGridViewExtensions_HideAllColumns">HideAllColumns Overload</a><br /><a href="N_DevCase_Core_Extensions_DataGridView">DevCase.Core.Extensions.DataGridView Namespace</a><br />