# DataGridViewExtensions.AddRange Method (DataColumnCollection, String[])
 

Creates and adds a System.Data.DataColumn object that has the specified name to the System.Data.DataColumnCollection DataColumnCollection.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DataColumnCollection">DevCase.Core.Extensions.DataColumnCollection</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static IEnumerable<DataColumn> AddRange(
	this DataColumnCollection sender,
	params string[] columnNames
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function AddRange ( 
	sender As DataColumnCollection,
	ParamArray columnNames As String()
) As IEnumerable(Of DataColumn)
```

**VB Usage**<br />
``` VB Usage
Dim sender As DataColumnCollection
Dim columnNames As String()
Dim returnValue As IEnumerable(Of DataColumn)

returnValue = sender.AddRange(columnNames)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static IEnumerable<DataColumn^>^ AddRange(
	DataColumnCollection^ sender, 
	... array<String^>^ columnNames
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AddRange : 
        sender : DataColumnCollection * 
        columnNames : string[] -> IEnumerable<DataColumn> 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Data.DataColumnCollection<br />The source DataColumnCollection.</dd><dt>columnNames</dt><dd>Type: System.String[]<br />The names of the columns to add.</dd></dl>

#### Return Value
Type: IEnumerable(DataColumn)<br />A collection with the newly created DataColumn.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DataColumnCollection. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DataColumnCollection_DataGridViewExtensions">DataGridViewExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_DataColumnCollection_DataGridViewExtensions_AddRange">AddRange Overload</a><br /><a href="N_DevCase_Core_Extensions_DataColumnCollection">DevCase.Core.Extensions.DataColumnCollection Namespace</a><br />