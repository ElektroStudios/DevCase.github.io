# XmlNodeExtensions.ToXNode Method 
 

Converts an XmlNode to XNode.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_XmlNode">DevCase.Core.Extensions.XmlNode</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static XNode ToXNode(
	this XmlNode sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToXNode ( 
	sender As XmlNode
) As XNode
```

**VB Usage**<br />
``` VB Usage
Dim sender As XmlNode
Dim returnValue As XNode

returnValue = sender.ToXNode()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static XNode^ ToXNode(
	XmlNode^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToXNode : 
        sender : XmlNode -> XNode 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Xml.XmlNode<br />The source XmlNode.</dd></dl>

#### Return Value
Type: XNode<br />The resulting XNode.

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

Dim xmlNode As XmlNode = xmlDoc.ChildNodes(0)
Dim xNode As XNode = xmlNode.ToXNode()

MessageBox.Show(xNode.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_XmlNode_XmlNodeExtensions">XmlNodeExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_XmlNode">DevCase.Core.Extensions.XmlNode Namespace</a><br />