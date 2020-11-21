# DataGridViewExtensions.HideColumns Method (DataGridView, Int32[])
 

Hides the specified columns of the DataGridView.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DataGridView">DevCase.Core.Extensions.DataGridView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void HideColumns(
	this DataGridView sender,
	int[] columnIndices
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub HideColumns ( 
	sender As DataGridView,
	columnIndices As Integer()
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As DataGridView
Dim columnIndices As Integer()

sender.HideColumns(columnIndices)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void HideColumns(
	DataGridView^ sender, 
	array<int>^ columnIndices
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member HideColumns : 
        sender : DataGridView * 
        columnIndices : int[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.DataGridView<br />The source DataGridView.</dd><dt>columnIndices</dt><dd>Type: System.Int32[]<br />The indices of the columns to hide.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DataGridView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DataGridView_DataGridViewExtensions">DataGridViewExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_DataGridView_DataGridViewExtensions_HideColumns">HideColumns Overload</a><br /><a href="N_DevCase_Core_Extensions_DataGridView">DevCase.Core.Extensions.DataGridView Namespace</a><br />