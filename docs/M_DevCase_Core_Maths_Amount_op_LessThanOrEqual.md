# Amount.LessThanOrEqual Operator 
 

Compares two <a href="T_DevCase_Core_Maths_Amount">Amount</a> of compatible units.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool operator <=(
	Amount first,
	Amount second
)
```

**VB**<br />
``` VB
Public Shared Operator <= ( 
	first As Amount,
	second As Amount
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim first As Amount
Dim second As Amount
Dim returnValue As Boolean

returnValue = (first <= second)
```

**C++**<br />
``` C++
public:
static bool operator <=(
	Amount^ first, 
	Amount^ second
)
```

**F#**<br />
``` F#
static let inline (<=)
        first : Amount * 
        second : Amount  : bool
```


#### Parameters
&nbsp;<dl><dt>first</dt><dd>Type: <a href="T_DevCase_Core_Maths_Amount">DevCase.Core.Maths.Amount</a><br />The first <a href="T_DevCase_Core_Maths_Amount">Amount</a>.</dd><dt>second</dt><dd>Type: <a href="T_DevCase_Core_Maths_Amount">DevCase.Core.Maths.Amount</a><br />The second <a href="T_DevCase_Core_Maths_Amount">Amount</a>.</dd></dl>

#### Return Value
Type: Boolean<br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />