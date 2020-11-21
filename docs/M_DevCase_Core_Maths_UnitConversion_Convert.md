# UnitConversion.Convert Method 
 

Converts the specified <a href="T_DevCase_Core_Maths_Amount">Amount</a> using the specified conversion function in <a href="P_DevCase_Core_Maths_UnitConversion_ConversionFunction">ConversionFunction</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Amount Convert(
	Amount amount
)
```

**VB**<br />
``` VB
Public Function Convert ( 
	amount As Amount
) As Amount
```

**VB Usage**<br />
``` VB Usage
Dim instance As UnitConversion
Dim amount As Amount
Dim returnValue As Amount

returnValue = instance.Convert(amount)
```

**C++**<br />
``` C++
public:
Amount^ Convert(
	Amount^ amount
)
```

**F#**<br />
``` F#
member Convert : 
        amount : Amount -> Amount 

```


#### Parameters
&nbsp;<dl><dt>amount</dt><dd>Type: <a href="T_DevCase_Core_Maths_Amount">DevCase.Core.Maths.Amount</a><br />The <a href="T_DevCase_Core_Maths_Amount">Amount</a> to convert.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Maths_Amount">Amount</a><br />The resulting <a href="T_DevCase_Core_Maths_Amount">Amount</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_UnitConversion">UnitConversion Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />