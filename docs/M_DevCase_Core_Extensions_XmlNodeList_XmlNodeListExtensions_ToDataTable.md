# XmlNodeListExtensions.ToDataTable Method 
 

Converts an XmlNodeList to DataTable.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_XmlNodeList">DevCase.Core.Extensions.XmlNodeList</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static DataTable ToDataTable(
	this XmlNodeList sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToDataTable ( 
	sender As XmlNodeList
) As DataTable
```

**VB Usage**<br />
``` VB Usage
Dim sender As XmlNodeList
Dim returnValue As DataTable

returnValue = sender.ToDataTable()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static DataTable^ ToDataTable(
	XmlNodeList^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToDataTable : 
        sender : XmlNodeList -> DataTable 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Xml.XmlNodeList<br />The source XmlNodeList.</dd></dl>

#### Return Value
Type: DataTable<br />The resulting DataTable.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type XmlNodeList. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_XmlNodeList_XmlNodeListExtensions">XmlNodeListExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_XmlNodeList">DevCase.Core.Extensions.XmlNodeList Namespace</a><br />