# DataGridViewExtensions.ShowAllColumns Method (DataGridView, String[])
 

Shows all the columns of the DataGridView, except the specified columns.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DataGridView">DevCase.Core.Extensions.DataGridView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void ShowAllColumns(
	this DataGridView sender,
	string[] excludeColumnNames
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub ShowAllColumns ( 
	sender As DataGridView,
	excludeColumnNames As String()
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As DataGridView
Dim excludeColumnNames As String()

sender.ShowAllColumns(excludeColumnNames)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void ShowAllColumns(
	DataGridView^ sender, 
	array<String^>^ excludeColumnNames
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ShowAllColumns : 
        sender : DataGridView * 
        excludeColumnNames : string[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.DataGridView<br />The source DataGridView.</dd><dt>excludeColumnNames</dt><dd>Type: System.String[]<br />The names of the columns to exclude.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DataGridView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DataGridView_DataGridViewExtensions">DataGridViewExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_DataGridView_DataGridViewExtensions_ShowAllColumns">ShowAllColumns Overload</a><br /><a href="N_DevCase_Core_Extensions_DataGridView">DevCase.Core.Extensions.DataGridView Namespace</a><br />