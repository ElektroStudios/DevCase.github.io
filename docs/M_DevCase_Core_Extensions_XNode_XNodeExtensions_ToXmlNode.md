# XNodeExtensions.ToXmlNode Method 
 

Converts an XNode to XmlNode.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_XNode">DevCase.Core.Extensions.XNode</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static XmlNode ToXmlNode(
	this XNode node
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToXmlNode ( 
	node As XNode
) As XmlNode
```

**VB Usage**<br />
``` VB Usage
Dim node As XNode
Dim returnValue As XmlNode

returnValue = node.ToXmlNode()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static XmlNode^ ToXmlNode(
	XNode^ node
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToXmlNode : 
        node : XNode -> XmlNode 

```


#### Parameters
&nbsp;<dl><dt>node</dt><dd>Type: System.Xml.Linq.XNode<br />The source Xml node.</dd></dl>

#### Return Value
Type: XmlNode<br />The resulting XmlNode.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type XNode. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim xDoc As XDocument =
    <?xml version="1.0" encoding="Windows-1252"?>
    <!--Xml Songs Database-->
    <Songs>
        <Song><Name>My Song 3.mp3</Name></Song>
        <Song><Name>My Song 1.mp3</Name></Song>
        <Song><Name>My Song 2.mp3</Name></Song>
    </Songs>

Dim xNode As XNode = xDoc.Nodes(1)
Dim xmlNode As XmlNode = xNode.ToXmlNode()

MessageBox.Show(xmlNode.InnerXml)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_XNode_XNodeExtensions">XNodeExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_XNode">DevCase.Core.Extensions.XNode Namespace</a><br />