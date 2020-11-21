# BBCodeNode.RemoveChild Method 
 

Removes a specific child node.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual BBCodeNode RemoveChild(
	BBCodeNode node
)
```

**VB**<br />
``` VB
Public Overridable Function RemoveChild ( 
	node As BBCodeNode
) As BBCodeNode
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeNode
Dim node As BBCodeNode
Dim returnValue As BBCodeNode

returnValue = instance.RemoveChild(node)
```

**C++**<br />
``` C++
public:
virtual BBCodeNode^ RemoveChild(
	BBCodeNode^ node
)
```

**F#**<br />
``` F#
abstract RemoveChild : 
        node : BBCodeNode -> BBCodeNode 
override RemoveChild : 
        node : BBCodeNode -> BBCodeNode 
```


#### Parameters
&nbsp;<dl><dt>node</dt><dd>Type: <a href="T_DevCase_Core_NET_BBCodeNode">DevCase.Core.NET.BBCodeNode</a><br />The child node to remove. 

 This must be a child of the current node.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a><br />The removed node.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />