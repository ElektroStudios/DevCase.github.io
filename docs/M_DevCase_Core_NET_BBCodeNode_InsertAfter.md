# BBCodeNode.InsertAfter Method 
 

Inserts a new child node after the reference node passed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual BBCodeNode InsertAfter(
	BBCodeNode node,
	BBCodeNode after
)
```

**VB**<br />
``` VB
Public Overridable Function InsertAfter ( 
	node As BBCodeNode,
	after As BBCodeNode
) As BBCodeNode
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeNode
Dim node As BBCodeNode
Dim after As BBCodeNode
Dim returnValue As BBCodeNode

returnValue = instance.InsertAfter(node, 
	after)
```

**C++**<br />
``` C++
public:
virtual BBCodeNode^ InsertAfter(
	BBCodeNode^ node, 
	BBCodeNode^ after
)
```

**F#**<br />
``` F#
abstract InsertAfter : 
        node : BBCodeNode * 
        after : BBCodeNode -> BBCodeNode 
override InsertAfter : 
        node : BBCodeNode * 
        after : BBCodeNode -> BBCodeNode 
```


#### Parameters
&nbsp;<dl><dt>node</dt><dd>Type: <a href="T_DevCase_Core_NET_BBCodeNode">DevCase.Core.NET.BBCodeNode</a><br />The new child node to add. 

 This may not be already childed to another node</dd><dt>after</dt><dd>Type: <a href="T_DevCase_Core_NET_BBCodeNode">DevCase.Core.NET.BBCodeNode</a><br />The reference node. 

 This must be a child of the current node</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a><br />The added node.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />