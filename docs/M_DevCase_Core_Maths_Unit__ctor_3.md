# Unit Constructor (String, String, Unit, UnitConversion[])
 

Initializes a new instance of the <a href="T_DevCase_Core_Maths_Unit">Unit</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Unit(
	string name,
	string symbol,
	Unit baseUnit,
	params UnitConversion[] unitConversions
)
```

**VB**<br />
``` VB
Public Sub New ( 
	name As String,
	symbol As String,
	baseUnit As Unit,
	ParamArray unitConversions As UnitConversion()
)
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim symbol As String
Dim baseUnit As Unit
Dim unitConversions As UnitConversion()

Dim instance As New Unit(name, symbol, 
	baseUnit, unitConversions)
```

**C++**<br />
``` C++
public:
Unit(
	String^ name, 
	String^ symbol, 
	Unit^ baseUnit, 
	... array<UnitConversion^>^ unitConversions
)
```

**F#**<br />
``` F#
new : 
        name : string * 
        symbol : string * 
        baseUnit : Unit * 
        unitConversions : UnitConversion[] -> Unit
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of this <a href="T_DevCase_Core_Maths_Unit">Unit</a>.</dd><dt>symbol</dt><dd>Type: System.String<br />The symbol of this <a href="T_DevCase_Core_Maths_Unit">Unit</a>.</dd><dt>baseUnit</dt><dd>Type: <a href="T_DevCase_Core_Maths_Unit">DevCase.Core.Maths.Unit</a><br />The base <a href="T_DevCase_Core_Maths_Unit">Unit</a> of this <a href="T_DevCase_Core_Maths_Unit">Unit</a>.</dd><dt>unitConversions</dt><dd>Type: <a href="T_DevCase_Core_Maths_UnitConversion">DevCase.Core.Maths.UnitConversion</a>[]<br />An array of <a href="T_DevCase_Core_Maths_UnitConversion">UnitConversion</a> containing conversion functions between this <a href="T_DevCase_Core_Maths_Unit">Unit</a> and another.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Unit">Unit Class</a><br /><a href="Overload_DevCase_Core_Maths_Unit__ctor">Unit Overload</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />