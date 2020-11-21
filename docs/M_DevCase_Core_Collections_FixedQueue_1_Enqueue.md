# FixedQueue(*T*).Enqueue Method 
 

Adds an object to the end of this <a href="T_DevCase_Core_Collections_FixedQueue_1">FixedQueue(T)</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void Enqueue(
	T item,
	bool throwIfFullSlots = false
)
```

**VB**<br />
``` VB
Public Sub Enqueue ( 
	item As T,
	Optional throwIfFullSlots As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FixedQueue
Dim item As T
Dim throwIfFullSlots As Boolean

instance.Enqueue(item, throwIfFullSlots)
```

**C++**<br />
``` C++
public:
void Enqueue(
	T item, 
	bool throwIfFullSlots = false
)
```

**F#**<br />
``` F#
member Enqueue : 
        item : 'T * 
        ?throwIfFullSlots : bool 
(* Defaults:
        let _throwIfFullSlots = defaultArg throwIfFullSlots false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>item</dt><dd>Type: <a href="T_DevCase_Core_Collections_FixedQueue_1">*T*</a><br />The object to add to the queue. 

 The value can be null for reference types.</dd><dt>throwIfFullSlots (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), a OverflowException is thrown if there isn't any free slot to add the item. 

 If `false` (`False` in Visual Basic) and there isn't any free slot to add the item, the last item on the queue is discarded.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>OverflowException</td><td>Any slot availiable.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Collections_FixedQueue_1">FixedQueue(T) Class</a><br /><a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />