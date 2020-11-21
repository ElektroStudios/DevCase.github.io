# ListViewExtensions.ExportToXml Method 
 

Exports the source ListView to `Xml` format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_ListView">DevCase.Core.Extensions.ListView</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ExportToXml(
	this ListView sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ExportToXml ( 
	sender As ListView
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As ListView
Dim returnValue As String

returnValue = sender.ExportToXml()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ExportToXml(
	ListView^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ExportToXml : 
        sender : ListView -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.ListView<br />The source ListView.</dd></dl>

#### Return Value
Type: String<br />The resulting `Xml` string.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type ListView. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lv As New ListView
lv.Columns.Add("column1")
lv.Columns.Add("column2")
lv.Columns.Add("column3")

lv.Items.Add("Item1").SubItems.AddRange({"SubItem1", "SubItem2"})
lv.Items.Add("Item2").SubItems.Add("SubItem1")
lv.Items.Add("Item3").SubItems.Add("SubItem1")

Dim xml As String = lv.ExportToXml()
Console.WriteLine(xml)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_ListView_ListViewExtensions">ListViewExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_ListView">DevCase.Core.Extensions.ListView Namespace</a><br />