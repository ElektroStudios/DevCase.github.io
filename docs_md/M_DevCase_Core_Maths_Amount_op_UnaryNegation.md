# Amount.UnaryNegation Operator 
 

Substracts an <a href="T_DevCase_Core_Maths_Amount">Amount</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Amount operator -(
	Amount second
)
```

**VB**<br />
``` VB
Public Shared Operator - ( 
	second As Amount
) As Amount
```

**VB Usage**<br />
``` VB Usage
Dim second As Amount
Dim returnValue As Amount

returnValue = -second
```

**C++**<br />
``` C++
public:
static Amount^ operator -(
	Amount^ second
)
```

**F#**<br />
``` F#
static let inline (-)
        second : Amount  : Amount
```


#### Parameters
&nbsp;<dl><dt>second</dt><dd>Type: <a href="T_DevCase_Core_Maths_Amount">DevCase.Core.Maths.Amount</a><br />The second <a href="T_DevCase_Core_Maths_Amount">Amount</a>.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Maths_Amount">Amount</a><br />The result of the operator.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />