# Unit.IsCompatibleWith Method 
 

Determines whether the specified <a href="T_DevCase_Core_Maths_Unit">Unit</a> is compatible with this one.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool IsCompatibleWith(
	Unit otherUnit
)
```

**VB**<br />
``` VB
Public Function IsCompatibleWith ( 
	otherUnit As Unit
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As Unit
Dim otherUnit As Unit
Dim returnValue As Boolean

returnValue = instance.IsCompatibleWith(otherUnit)
```

**C++**<br />
``` C++
public:
bool IsCompatibleWith(
	Unit^ otherUnit
)
```

**F#**<br />
``` F#
member IsCompatibleWith : 
        otherUnit : Unit -> bool 

```


#### Parameters
&nbsp;<dl><dt>otherUnit</dt><dd>Type: <a href="T_DevCase_Core_Maths_Unit">DevCase.Core.Maths.Unit</a><br />The <a href="T_DevCase_Core_Maths_Unit">Unit</a> to check compatibility with.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) ifthe specified <a href="T_DevCase_Core_Maths_Unit">Unit</a> is compatible with this one; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Unit">Unit Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />