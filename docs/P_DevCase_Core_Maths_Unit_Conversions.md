# Unit.Conversions Property 
 

Gets an array of <a href="T_DevCase_Core_Maths_UnitConversion">UnitConversion</a> containing conversion functions between this <a href="T_DevCase_Core_Maths_Unit">Unit</a> and another.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public UnitConversion[] Conversions { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Conversions As UnitConversion()
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As Unit
Dim value As UnitConversion()

value = instance.Conversions

```

**C++**<br />
``` C++
public:
property array<UnitConversion^>^ Conversions {
	array<UnitConversion^>^ get ();
}
```

**F#**<br />
``` F#
member Conversions : UnitConversion[] with get

```


#### Property Value
Type: <a href="T_DevCase_Core_Maths_UnitConversion">UnitConversion</a>[]<br />An array of <a href="T_DevCase_Core_Maths_UnitConversion">UnitConversion</a> containing conversion functions between this <a href="T_DevCase_Core_Maths_Unit">Unit</a> and another.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Unit">Unit Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />