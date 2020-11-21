# UnitConversionException Constructor (Unit, Unit)
 

Initializes a new instance of the <a href="T_DevCase_Core_Maths_Exceptions_UnitConversionException">UnitConversionException</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths_Exceptions">DevCase.Core.Maths.Exceptions</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public UnitConversionException(
	Unit fromUnit,
	Unit toUnit
)
```

**VB**<br />
``` VB
Public Sub New ( 
	fromUnit As Unit,
	toUnit As Unit
)
```

**VB Usage**<br />
``` VB Usage
Dim fromUnit As Unit
Dim toUnit As Unit

Dim instance As New UnitConversionException(fromUnit, 
	toUnit)
```

**C++**<br />
``` C++
public:
UnitConversionException(
	Unit^ fromUnit, 
	Unit^ toUnit
)
```

**F#**<br />
``` F#
new : 
        fromUnit : Unit * 
        toUnit : Unit -> UnitConversionException
```


#### Parameters
&nbsp;<dl><dt>fromUnit</dt><dd>Type: <a href="T_DevCase_Core_Maths_Unit">DevCase.Core.Maths.Unit</a><br />The <a href="T_DevCase_Core_Maths_Unit">Unit</a> to convert from.</dd><dt>toUnit</dt><dd>Type: <a href="T_DevCase_Core_Maths_Unit">DevCase.Core.Maths.Unit</a><br />The <a href="T_DevCase_Core_Maths_Unit">Unit</a> to convert to.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Exceptions_UnitConversionException">UnitConversionException Class</a><br /><a href="Overload_DevCase_Core_Maths_Exceptions_UnitConversionException__ctor">UnitConversionException Overload</a><br /><a href="N_DevCase_Core_Maths_Exceptions">DevCase.Core.Maths.Exceptions Namespace</a><br />