# DataGridViewExtensions.ExportToXml Method 
 

Exports the source DataGridView to `Xml` format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DataGridView">DevCase.Core.Extensions.DataGridView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ExportToXml(
	this DataGridView sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ExportToXml ( 
	sender As DataGridView
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As DataGridView
Dim returnValue As String

returnValue = sender.ExportToXml()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ExportToXml(
	DataGridView^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ExportToXml : 
        sender : DataGridView -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.DataGridView<br />The source DataGridView.</dd></dl>

#### Return Value
Type: String<br />The resulting `Xml` string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DataGridView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dgv As New DataGridView
With dgv
    .Columns.Add(columnName:="Column1", headerText:="Column1")
    .Columns.Add(columnName:="Column2", headerText:="Column2")
    .Columns.Add(columnName:="Column3", headerText:="Column3")

    .Rows.Add({"Cell A1", "Cell A2"})
    .Rows.Add({"Cell B1", "Cell B2", "Cell B3"})
    .Rows.Add({"Cell C1", "Cell C2", "Cell C3"})
End With

Dim xml As String = dgv.ExportToXml()
Console.WriteLine(xml)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DataGridView_DataGridViewExtensions">DataGridViewExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DataGridView">DevCase.Core.Extensions.DataGridView Namespace</a><br />