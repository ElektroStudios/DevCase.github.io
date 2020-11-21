# Unit.IComparable(Unit).CompareTo Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
int IComparable<Unit>.CompareTo(
	Unit otherUnit
)
```

**VB**<br />
``` VB
Private Function IComparable_CompareTo ( 
	otherUnit As Unit
) As Integer Implements IComparable(Of Unit).CompareTo
```

**VB Usage**<br />
``` VB Usage
Dim instance As Unit
Dim otherUnit As Unit
Dim returnValue As Integer

returnValue = CType(instance, IComparable(Of Unit)).CompareTo(otherUnit)
```

**C++**<br />
``` C++
private:
virtual int IComparable_CompareTo(
	Unit^ otherUnit
) sealed = IComparable<Unit^>::CompareTo
```

**F#**<br />
``` F#
private abstract IComparable_CompareTo : 
        otherUnit : Unit -> int 
private override IComparable_CompareTo : 
        otherUnit : Unit -> int 
```


#### Parameters
&nbsp;<dl><dt>otherUnit</dt><dd>Type: <a href="T_DevCase_Core_Maths_Unit">DevCase.Core.Maths.Unit</a><br />\[Missing <param name="otherUnit"/> documentation for "M:DevCase.Core.Maths.Unit.System#IComparable{DevCase#Core#Maths#Unit}#CompareTo(DevCase.Core.Maths.Unit)"\]</dd></dl>

#### Return Value
Type: Int32<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Unit.System#IComparable{DevCase#Core#Maths#Unit}#CompareTo(DevCase.Core.Maths.Unit)"\]

#### Implements
IComparable(T).CompareTo(T)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Unit">Unit Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />