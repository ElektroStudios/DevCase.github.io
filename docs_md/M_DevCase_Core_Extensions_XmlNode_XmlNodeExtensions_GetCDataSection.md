# XmlNodeExtensions.GetCDataSection Method 
 

Gets the content of a nested CData section.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_XmlNode">DevCase.Core.Extensions.XmlNode</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string GetCDataSection(
	this XmlNode parentNode
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetCDataSection ( 
	parentNode As XmlNode
) As String
```

**VB Usage**<br />
``` VB Usage
Dim parentNode As XmlNode
Dim returnValue As String

returnValue = parentNode.GetCDataSection()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ GetCDataSection(
	XmlNode^ parentNode
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetCDataSection : 
        parentNode : XmlNode -> string 

```


#### Parameters
&nbsp;<dl><dt>parentNode</dt><dd>Type: System.Xml.XmlNode<br />The parent node.</dd></dl>

#### Return Value
Type: String<br />The content of the CData section.

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

xmlDoc.ChildNodes(0).CreateCDataSection("This is the CDATA Text.")
MessageBox.Show(xmlDoc.ChildNodes(0).GetCDataSection())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_XmlNode_XmlNodeExtensions">XmlNodeExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_XmlNode">DevCase.Core.Extensions.XmlNode Namespace</a><br />