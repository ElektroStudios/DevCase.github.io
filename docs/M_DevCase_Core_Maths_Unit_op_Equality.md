# Unit.Equality Operator 
 

Implements the operator =

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool operator ==(
	Unit first,
	Unit second
)
```

**VB**<br />
``` VB
Public Shared Operator = ( 
	first As Unit,
	second As Unit
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim first As Unit
Dim second As Unit
Dim returnValue As Boolean

returnValue = (first = second)
```

**C++**<br />
``` C++
public:
static bool operator ==(
	Unit^ first, 
	Unit^ second
)
```

**F#**<br />
``` F#
static let inline (=)
        first : Unit * 
        second : Unit  : bool
```


#### Parameters
&nbsp;<dl><dt>first</dt><dd>Type: <a href="T_DevCase_Core_Maths_Unit">DevCase.Core.Maths.Unit</a><br />The first value.</dd><dt>second</dt><dd>Type: <a href="T_DevCase_Core_Maths_Unit">DevCase.Core.Maths.Unit</a><br />The second value.</dd></dl>

#### Return Value
Type: Boolean<br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Unit">Unit Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />