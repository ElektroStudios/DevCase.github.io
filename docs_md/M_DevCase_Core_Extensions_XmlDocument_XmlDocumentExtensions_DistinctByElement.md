# XmlDocumentExtensions.DistinctByElement Method 
 

Deletes duplicated values by the specified element of an XmlDocument.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_XmlDocument">DevCase.Core.Extensions.XmlDocument</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static XmlDocument DistinctByElement(
	this XmlDocument sender,
	string rootElementName,
	string elementName
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function DistinctByElement ( 
	sender As XmlDocument,
	rootElementName As String,
	elementName As String
) As XmlDocument
```

**VB Usage**<br />
``` VB Usage
Dim sender As XmlDocument
Dim rootElementName As String
Dim elementName As String
Dim returnValue As XmlDocument

returnValue = sender.DistinctByElement(rootElementName, 
	elementName)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static XmlDocument^ DistinctByElement(
	XmlDocument^ sender, 
	String^ rootElementName, 
	String^ elementName
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member DistinctByElement : 
        sender : XmlDocument * 
        rootElementName : string * 
        elementName : string -> XmlDocument 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Xml.XmlDocument<br />The source XmlDocument.</dd><dt>rootElementName</dt><dd>Type: System.String<br />The root Xml element name.</dd><dt>elementName</dt><dd>Type: System.String<br />The element name to remove its duplicated values.</dd></dl>

#### Return Value
Type: XmlDocument<br />The resulting XmlDocument.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type XmlDocument. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim xml As String =
    <Songs>
        <Song><Name>My Song 1.mp3</Name></Song>
        <Song><Name>My Song 1.mp3</Name></Song>
        <Song><Name>My Song 2.mp3</Name></Song>
    </Songs>.ToString()

Dim xmlDoc As New XmlDocument
xmlDoc.LoadXml(xml)

xmlDoc = xmlDoc.DistinctByElement(rootElementName:="Song", elementName:="Name")
MessageBox.Show(xmlDoc.InnerXml)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_XmlDocument_XmlDocumentExtensions">XmlDocumentExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_XmlDocument">DevCase.Core.Extensions.XmlDocument Namespace</a><br />