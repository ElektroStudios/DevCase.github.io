# BBCodeNode.AppendChild Method (BBCodeNode)
 

Adds a new child node at the end of this node's descendants.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual BBCodeNode AppendChild(
	BBCodeNode node
)
```

**VB**<br />
``` VB
Public Overridable Function AppendChild ( 
	node As BBCodeNode
) As BBCodeNode
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeNode
Dim node As BBCodeNode
Dim returnValue As BBCodeNode

returnValue = instance.AppendChild(node)
```

**C++**<br />
``` C++
public:
virtual BBCodeNode^ AppendChild(
	BBCodeNode^ node
)
```

**F#**<br />
``` F#
abstract AppendChild : 
        node : BBCodeNode -> BBCodeNode 
override AppendChild : 
        node : BBCodeNode -> BBCodeNode 
```


#### Parameters
&nbsp;<dl><dt>node</dt><dd>Type: <a href="T_DevCase_Core_NET_BBCodeNode">DevCase.Core.NET.BBCodeNode</a><br />The existing BBCodeNode to add. 

 This may not already be childed to another node.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a><br />The node passed.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode Class</a><br /><a href="Overload_DevCase_Core_NET_BBCodeNode_AppendChild">AppendChild Overload</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />