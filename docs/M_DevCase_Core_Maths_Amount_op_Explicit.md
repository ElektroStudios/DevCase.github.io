# Amount&nbsp;Explicit Conversion (Amount to Nullable(Double))
 

Casts an <a href="T_DevCase_Core_Maths_Amount">Amount</a> to a double.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static explicit operator Nullable<double> (
	Amount amount
)
```

**VB**<br />
``` VB
Public Shared Narrowing Operator CType ( 
	amount As Amount
) As Nullable(Of Double)
```

**VB Usage**<br />
``` VB Usage
Dim input As Amount
Dim output As Nullable(Of Double)

output = CType(input, Nullable(Of Double))
```

**C++**<br />
``` C++
static explicit operator Nullable<double> (
	Amount^ amount
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>amount</dt><dd>Type: <a href="T_DevCase_Core_Maths_Amount">DevCase.Core.Maths.Amount</a><br />The amount.</dd></dl>

#### Return Value
Type: Nullable(Double)<br />The result of the conversion.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />