# Unit.Equals Method (Unit)
 

Determines whether the specified <a href="T_DevCase_Core_Maths_Unit">Unit</a> is equal to this instance.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool Equals(
	Unit unit
)
```

**VB**<br />
``` VB
Public Function Equals ( 
	unit As Unit
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As Unit
Dim unit As Unit
Dim returnValue As Boolean

returnValue = instance.Equals(unit)
```

**C++**<br />
``` C++
public:
virtual bool Equals(
	Unit^ unit
) sealed
```

**F#**<br />
``` F#
abstract Equals : 
        unit : Unit -> bool 
override Equals : 
        unit : Unit -> bool 
```


#### Parameters
&nbsp;<dl><dt>unit</dt><dd>Type: <a href="T_DevCase_Core_Maths_Unit">DevCase.Core.Maths.Unit</a><br />Another <a href="T_DevCase_Core_Maths_Unit">Unit</a> to compare to.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified <a href="T_DevCase_Core_Maths_Unit">Unit</a> is equal to this instance; otherwise, `false` (`False` in Visual Basic).

#### Implements
IEquatable(T).Equals(T)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Unit">Unit Class</a><br /><a href="Overload_DevCase_Core_Maths_Unit_Equals">Equals Overload</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />