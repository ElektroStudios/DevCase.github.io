# BBCodeNode.Item Property (Int32)
 

Gets the child <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public BBCodeNode this[
	int index
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Item ( 
	index As Integer
) As BBCodeNode
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeNode
Dim index As Integer
Dim value As BBCodeNode

value = instance.Item(index)

```

**C++**<br />
``` C++
public:
property BBCodeNode^ Item[int index] {
	BBCodeNode^ get (int index);
}
```

**F#**<br />
``` F#
member Item : BBCodeNode with get

```


#### Parameters
&nbsp;<dl><dt>index</dt><dd>Type: System.Int32<br />The index of the <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a> to access.</dd></dl>

#### Property Value
Type: <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a><br />The <a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a> item at the specified index.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode Class</a><br /><a href="Overload_DevCase_Core_NET_BBCodeNode_Item">Item Overload</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />