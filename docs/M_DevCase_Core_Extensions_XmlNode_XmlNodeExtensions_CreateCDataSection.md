# XmlNodeExtensions.CreateCDataSection Method (XmlNode)
 

Appends a CData section to a Xml node.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_XmlNode">DevCase.Core.Extensions.XmlNode</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static XmlCDataSection CreateCDataSection(
	this XmlNode parentNode
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function CreateCDataSection ( 
	parentNode As XmlNode
) As XmlCDataSection
```

**VB Usage**<br />
``` VB Usage
Dim parentNode As XmlNode
Dim returnValue As XmlCDataSection

returnValue = parentNode.CreateCDataSection()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static XmlCDataSection^ CreateCDataSection(
	XmlNode^ parentNode
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CreateCDataSection : 
        parentNode : XmlNode -> XmlCDataSection 

```


#### Parameters
&nbsp;<dl><dt>parentNode</dt><dd>Type: System.Xml.XmlNode<br />The parent node.</dd></dl>

#### Return Value
Type: XmlCDataSection<br />The resulting XmlCDataSection.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type XmlNode. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim xml As String =
    <Songs>
        <Song><Name>My Song 3.mp3</Name></Song>
        <Song><Name>My Song 1.mp3</Name></Song>
        <Song><Name>My Song 2.mp3</Name></Song>
    </Songs>.ToString()

Dim xmlDoc As New XmlDocument
xmlDoc.LoadXml(xml)

xmlDoc.ChildNodes(0).CreateCDataSection()
MessageBox.Show(xmlDoc.ChildNodes(0).InnerXml)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_XmlNode_XmlNodeExtensions">XmlNodeExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_XmlNode_XmlNodeExtensions_CreateCDataSection">CreateCDataSection Overload</a><br /><a href="N_DevCase_Core_Extensions_XmlNode">DevCase.Core.Extensions.XmlNode Namespace</a><br />