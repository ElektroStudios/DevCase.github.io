# BBCodeNode.AppendChild Method (String, String)
 

Adds a new child node at the end of this node's descendants

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual BBCodeNode AppendChild(
	string tagName,
	string attribute
)
```

**VB**<br />
``` VB
Public Overridable Function AppendChild ( 
	tagName As String,
	attribute As String
) As BBCodeNode
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeNode
Dim tagName As String
Dim attribute As String
Dim returnValue As BBCodeNode

returnValue = instance.AppendChild(tagName, 
	attribute)
```

**C++**<br />
``` C++
public:
virtual BBCodeNode^ AppendChild(
	String^ tagName, 
	String^ attribute
)
```

**F#**<br />
``` F#
abstract AppendChild : 
        tagName : string * 
        attribute : string -> BBCodeNode 
override AppendChild : 
        tagName : string * 
        attribute : string -> BBCodeNode 
```


#### Parameters
&nbsp;<dl><dt>tagName</dt><dd>Type: System.String<br />The node's tag name. Mandatory.</dd><dt>attribute</dt><dd>Type: System.String<br />The node's optional attribute. 

 This may be an empty string or null.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a><br />The newly created child node.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode Class</a><br /><a href="Overload_DevCase_Core_NET_BBCodeNode_AppendChild">AppendChild Overload</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />