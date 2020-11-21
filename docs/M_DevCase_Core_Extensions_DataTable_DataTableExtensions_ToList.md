# DataTableExtensions.ToList Method 
 

Converts the source DataTable to a List(T).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DataTable">DevCase.Core.Extensions.DataTable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static List<Dictionary<string, Object>> ToList(
	this DataTable sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToList ( 
	sender As DataTable
) As List(Of Dictionary(Of String, Object))
```

**VB Usage**<br />
``` VB Usage
Dim sender As DataTable
Dim returnValue As List(Of Dictionary(Of String, Object))

returnValue = sender.ToList()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static List<Dictionary<String^, Object^>^>^ ToList(
	DataTable^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToList : 
        sender : DataTable -> List<Dictionary<string, Object>> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Data.DataTable<br />The source DataTable.</dd></dl>

#### Return Value
Type: List(Dictionary(String, Object))<br />The resulting List(T).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DataTable. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dt As New DataTable()
dt.Columns.Add("Name", GetType(String))
dt.Columns.Add("Date", GetType(Date))
dt.Rows.Add("Elektro", Date.Parse("01-01-2016"))

Dim list As List(Of Dictionary(Of String, Object)) = dt.ToList()

For Each dict As Dictionary(Of String, Object) In list
    For Each key As String In dict.Keys
        Console.WriteLine("Name: {0}, Value:{1}", key, dict(key).ToString())
    Next
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DataTable_DataTableExtensions">DataTableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DataTable">DevCase.Core.Extensions.DataTable Namespace</a><br />