# Amount.Division Operator (Amount, Double)
 

Divides an <a href="T_DevCase_Core_Maths_Amount">Amount</a> by a Double value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Amount operator /(
	Amount first,
	double second
)
```

**VB**<br />
``` VB
Public Shared Operator / ( 
	first As Amount,
	second As Double
) As Amount
```

**VB Usage**<br />
``` VB Usage
Dim first As Amount
Dim second As Double
Dim returnValue As Amount

returnValue = (first / second)
```

**C++**<br />
``` C++
public:
static Amount^ operator /(
	Amount^ first, 
	double second
)
```

**F#**<br />
``` F#
static let inline (/)
        first : Amount * 
        second : float  : Amount
```


#### Parameters
&nbsp;<dl><dt>first</dt><dd>Type: <a href="T_DevCase_Core_Maths_Amount">DevCase.Core.Maths.Amount</a><br />The <a href="T_DevCase_Core_Maths_Amount">Amount</a> value.</dd><dt>second</dt><dd>Type: System.Double<br />The Double value.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Maths_Amount">Amount</a><br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="Overload_DevCase_Core_Maths_Amount_op_Division">Division Overload</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />