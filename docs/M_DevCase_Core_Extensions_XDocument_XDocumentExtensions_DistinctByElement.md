# XDocumentExtensions.DistinctByElement Method 
 

Deletes duplicated values by the specified element of an XDocument.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_XDocument">DevCase.Core.Extensions.XDocument</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static XDocument DistinctByElement(
	this XDocument sender,
	string rootElementName,
	string elementName
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function DistinctByElement ( 
	sender As XDocument,
	rootElementName As String,
	elementName As String
) As XDocument
```

**VB Usage**<br />
``` VB Usage
Dim sender As XDocument
Dim rootElementName As String
Dim elementName As String
Dim returnValue As XDocument

returnValue = sender.DistinctByElement(rootElementName, 
	elementName)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static XDocument^ DistinctByElement(
	XDocument^ sender, 
	String^ rootElementName, 
	String^ elementName
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member DistinctByElement : 
        sender : XDocument * 
        rootElementName : string * 
        elementName : string -> XDocument 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Xml.Linq.XDocument<br />The source XDocument.</dd><dt>rootElementName</dt><dd>Type: System.String<br />The root Xml element name.</dd><dt>elementName</dt><dd>Type: System.String<br />The element name to remove its duplicated values.</dd></dl>

#### Return Value
Type: XDocument<br />The XDocument.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type XDocument. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim xDoc As XDocument =
    <?xml version="1.0" encoding="Windows-1252"?>
    <!--Xml Songs Database-->
    <Songs>
        <Song><Name>My Song 1.mp3</Name></Song>
        <Song><Name>My Song 1.mp3</Name></Song>
        <Song><Name>My Song 2.mp3</Name></Song>
    </Songs>

xDoc = xDoc.DistinctByElement(rootElementName:="Song", elementName:="Name")
MessageBox.Show(xDoc.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_XDocument_XDocumentExtensions">XDocumentExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_XDocument">DevCase.Core.Extensions.XDocument Namespace</a><br />