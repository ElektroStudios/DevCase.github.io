# Amount.IComparable.CompareTo Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
int IComparable.CompareTo(
	Object obj
)
```

**VB**<br />
``` VB
Private Function IComparable_CompareTo ( 
	obj As Object
) As Integer Implements IComparable.CompareTo
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim obj As Object
Dim returnValue As Integer

returnValue = CType(instance, IComparable).CompareTo(obj)
```

**C++**<br />
``` C++
private:
virtual int IComparable_CompareTo(
	Object^ obj
) sealed = IComparable::CompareTo
```

**F#**<br />
``` F#
private abstract IComparable_CompareTo : 
        obj : Object -> int 
private override IComparable_CompareTo : 
        obj : Object -> int 
```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: System.Object<br />\[Missing <param name="obj"/> documentation for "M:DevCase.Core.Maths.Amount.System#IComparable#CompareTo(System.Object)"\]</dd></dl>

#### Return Value
Type: Int32<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IComparable#CompareTo(System.Object)"\]

#### Implements
IComparable.CompareTo(Object)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />