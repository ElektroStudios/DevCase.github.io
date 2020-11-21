# Amount.Equals Method (Amount)
 

Determines whether the specified <a href="T_DevCase_Core_Maths_Amount">Amount</a> is equal to the current one.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool Equals(
	Amount amount
)
```

**VB**<br />
``` VB
Public Function Equals ( 
	amount As Amount
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim amount As Amount
Dim returnValue As Boolean

returnValue = instance.Equals(amount)
```

**C++**<br />
``` C++
public:
virtual bool Equals(
	Amount^ amount
) sealed
```

**F#**<br />
``` F#
abstract Equals : 
        amount : Amount -> bool 
override Equals : 
        amount : Amount -> bool 
```


#### Parameters
&nbsp;<dl><dt>amount</dt><dd>Type: <a href="T_DevCase_Core_Maths_Amount">DevCase.Core.Maths.Amount</a><br />The <a href="T_DevCase_Core_Maths_Amount">Amount</a> to compare with the current one.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified <a href="T_DevCase_Core_Maths_Amount">Amount</a> is equal to the current one; otherwise, `false` (`False` in Visual Basic).

#### Implements
IEquatable(T).Equals(T)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="Overload_DevCase_Core_Maths_Amount_Equals">Equals Overload</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />