# Amount.ConvertedTo Method (Unit)
 

Returns an <a href="T_DevCase_Core_Maths_Amount">Amount</a> converted to the specified <a href="T_DevCase_Core_Maths_Unit">Unit</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Amount ConvertedTo(
	Unit unit
)
```

**VB**<br />
``` VB
Public Function ConvertedTo ( 
	unit As Unit
) As Amount
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim unit As Unit
Dim returnValue As Amount

returnValue = instance.ConvertedTo(unit)
```

**C++**<br />
``` C++
public:
Amount^ ConvertedTo(
	Unit^ unit
)
```

**F#**<br />
``` F#
member ConvertedTo : 
        unit : Unit -> Amount 

```


#### Parameters
&nbsp;<dl><dt>unit</dt><dd>Type: <a href="T_DevCase_Core_Maths_Unit">DevCase.Core.Maths.Unit</a><br />The <a href="T_DevCase_Core_Maths_Unit">Unit</a> to converto to.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Maths_Amount">Amount</a><br />The resulting <a href="T_DevCase_Core_Maths_Amount">Amount</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="Overload_DevCase_Core_Maths_Amount_ConvertedTo">ConvertedTo Overload</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />