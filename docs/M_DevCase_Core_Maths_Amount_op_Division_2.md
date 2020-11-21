# Amount.Division Operator (Double, Amount)
 

Divides a Double value by an <a href="T_DevCase_Core_Maths_Amount">Amount</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Amount operator /(
	double first,
	Amount second
)
```

**VB**<br />
``` VB
Public Shared Operator / ( 
	first As Double,
	second As Amount
) As Amount
```

**VB Usage**<br />
``` VB Usage
Dim first As Double
Dim second As Amount
Dim returnValue As Amount

returnValue = (first / second)
```

**C++**<br />
``` C++
public:
static Amount^ operator /(
	double first, 
	Amount^ second
)
```

**F#**<br />
``` F#
static let inline (/)
        first : float * 
        second : Amount  : Amount
```


#### Parameters
&nbsp;<dl><dt>first</dt><dd>Type: System.Double<br />The Double value.</dd><dt>second</dt><dd>Type: <a href="T_DevCase_Core_Maths_Amount">DevCase.Core.Maths.Amount</a><br />The <a href="T_DevCase_Core_Maths_Amount">Amount</a> value.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Maths_Amount">Amount</a><br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="Overload_DevCase_Core_Maths_Amount_op_Division">Division Overload</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />