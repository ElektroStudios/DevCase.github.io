# Unit.Multiply Operator (Unit, Double)
 

Implements the operator *

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Unit operator *(
	Unit first,
	double second
)
```

**VB**<br />
``` VB
Public Shared Operator * ( 
	first As Unit,
	second As Double
) As Unit
```

**VB Usage**<br />
``` VB Usage
Dim first As Unit
Dim second As Double
Dim returnValue As Unit

returnValue = (first * second)
```

**C++**<br />
``` C++
public:
static Unit^ operator *(
	Unit^ first, 
	double second
)
```

**F#**<br />
``` F#
static let inline (*)
        first : Unit * 
        second : float  : Unit
```


#### Parameters
&nbsp;<dl><dt>first</dt><dd>Type: <a href="T_DevCase_Core_Maths_Unit">DevCase.Core.Maths.Unit</a><br />The first value.</dd><dt>second</dt><dd>Type: System.Double<br />The second value.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Maths_Unit">Unit</a><br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Unit">Unit Class</a><br /><a href="Overload_DevCase_Core_Maths_Unit_op_Multiply">Multiply Overload</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />