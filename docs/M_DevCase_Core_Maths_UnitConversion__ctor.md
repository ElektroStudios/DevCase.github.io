# UnitConversion Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Maths_UnitConversion">UnitConversion</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public UnitConversion(
	string fromUnitName,
	string toUnitName,
	Func<Amount, Amount> conversionFunction
)
```

**VB**<br />
``` VB
Public Sub New ( 
	fromUnitName As String,
	toUnitName As String,
	conversionFunction As Func(Of Amount, Amount)
)
```

**VB Usage**<br />
``` VB Usage
Dim fromUnitName As String
Dim toUnitName As String
Dim conversionFunction As Func(Of Amount, Amount)

Dim instance As New UnitConversion(fromUnitName, 
	toUnitName, conversionFunction)
```

**C++**<br />
``` C++
public:
UnitConversion(
	String^ fromUnitName, 
	String^ toUnitName, 
	Func<Amount^, Amount^>^ conversionFunction
)
```

**F#**<br />
``` F#
new : 
        fromUnitName : string * 
        toUnitName : string * 
        conversionFunction : Func<Amount, Amount> -> UnitConversion
```


#### Parameters
&nbsp;<dl><dt>fromUnitName</dt><dd>Type: System.String<br />The name of the <a href="T_DevCase_Core_Maths_Unit">Unit</a> to convert from</dd><dt>toUnitName</dt><dd>Type: System.String<br />The name of the <a href="T_DevCase_Core_Maths_Unit">Unit</a> to convert to.</dd><dt>conversionFunction</dt><dd>Type: System.Func(<a href="T_DevCase_Core_Maths_Amount">Amount</a>, <a href="T_DevCase_Core_Maths_Amount">Amount</a>)<br />The conversion function used to convert the <a href="T_DevCase_Core_Maths_Amount">Amount</a>.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_UnitConversion">UnitConversion Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />