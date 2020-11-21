# BBCodeNode.InsertBefore Method 
 

Inserts a new child node before the reference node passed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual BBCodeNode InsertBefore(
	BBCodeNode node,
	BBCodeNode before
)
```

**VB**<br />
``` VB
Public Overridable Function InsertBefore ( 
	node As BBCodeNode,
	before As BBCodeNode
) As BBCodeNode
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeNode
Dim node As BBCodeNode
Dim before As BBCodeNode
Dim returnValue As BBCodeNode

returnValue = instance.InsertBefore(node, 
	before)
```

**C++**<br />
``` C++
public:
virtual BBCodeNode^ InsertBefore(
	BBCodeNode^ node, 
	BBCodeNode^ before
)
```

**F#**<br />
``` F#
abstract InsertBefore : 
        node : BBCodeNode * 
        before : BBCodeNode -> BBCodeNode 
override InsertBefore : 
        node : BBCodeNode * 
        before : BBCodeNode -> BBCodeNode 
```


#### Parameters
&nbsp;<dl><dt>node</dt><dd>Type: <a href="T_DevCase_Core_NET_BBCodeNode">DevCase.Core.NET.BBCodeNode</a><br />The new child node to add. 

 This may not be already childed to another node</dd><dt>before</dt><dd>Type: <a href="T_DevCase_Core_NET_BBCodeNode">DevCase.Core.NET.BBCodeNode</a><br />The reference node. 

 This must be a child of the current node</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a><br />The added node.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />