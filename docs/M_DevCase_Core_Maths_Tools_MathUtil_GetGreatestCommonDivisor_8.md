# MathUtil.GetGreatestCommonDivisor Method (UInt16[])
 

Gets the Greatest Common Divisor (GCD) of one or more values. 

 That is, the largest positive value that divides each of the given values. For example, the GCD of 8 and 12 is 4.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ushort GetGreatestCommonDivisor(
	params ushort[] values
)
```

**VB**<br />
``` VB
Public Shared Function GetGreatestCommonDivisor ( 
	ParamArray values As UShort()
) As UShort
```

**VB Usage**<br />
``` VB Usage
Dim values As UShort()
Dim returnValue As UShort

returnValue = MathUtil.GetGreatestCommonDivisor(values)
```

**C++**<br />
``` C++
public:
static unsigned short GetGreatestCommonDivisor(
	... array<unsigned short>^ values
)
```

**F#**<br />
``` F#
static member GetGreatestCommonDivisor : 
        values : uint16[] -> uint16 

```


#### Parameters
&nbsp;<dl><dt>values</dt><dd>Type: System.UInt16[]<br />The values.</dd></dl>

#### Return Value
Type: UInt16<br />The resulting Greatest Common Divisor (GCD).

## Remarks
Wikipedia article: <a href="https://en.wikipedia.org/wiki/Greatest_common_divisor" target="_blank">https://en.wikipedia.org/wiki/Greatest_common_divisor</a>

 Original solution in C#: <a href="https://stackoverflow.com/a/41766138/1248295" target="_blank">https://stackoverflow.com/a/41766138/1248295</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Tools_MathUtil">MathUtil Class</a><br /><a href="Overload_DevCase_Core_Maths_Tools_MathUtil_GetGreatestCommonDivisor">GetGreatestCommonDivisor Overload</a><br /><a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools Namespace</a><br />