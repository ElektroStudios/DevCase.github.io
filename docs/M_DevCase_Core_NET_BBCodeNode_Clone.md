# BBCodeNode.Clone Method 
 

Creates a recursive copy of the current nodes and its children.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Object Clone()
```

**VB**<br />
``` VB
Public Overridable Function Clone As Object
```

**VB Usage**<br />
``` VB Usage
Dim instance As BBCodeNode
Dim returnValue As Object

returnValue = instance.Clone()
```

**C++**<br />
``` C++
public:
virtual Object^ Clone()
```

**F#**<br />
``` F#
abstract Clone : unit -> Object 
override Clone : unit -> Object 
```


#### Return Value
Type: Object<br />A deep clone of the current node.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />