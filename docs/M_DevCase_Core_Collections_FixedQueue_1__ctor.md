# FixedQueue(*T*) Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Collections_FixedQueue_1">FixedQueue(T)</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FixedQueue(
	int maxCapacity
)
```

**VB**<br />
``` VB
Public Sub New ( 
	maxCapacity As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim maxCapacity As Integer

Dim instance As New FixedQueue(maxCapacity)
```

**C++**<br />
``` C++
public:
FixedQueue(
	int maxCapacity
)
```

**F#**<br />
``` F#
new : 
        maxCapacity : int -> FixedQueue
```


#### Parameters
&nbsp;<dl><dt>maxCapacity</dt><dd>Type: System.Int32<br />The maximum queue capacity. 

 Bottom items beyond the specified capacity are discarded when a new item is pushed.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Collections_FixedQueue_1">FixedQueue(T) Class</a><br /><a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />