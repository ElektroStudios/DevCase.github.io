# MathUtil.ConvertSize Method 
 

Convert between sizes based in bytes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double ConvertSize(
	double size,
	SizeUnits fromUnit,
	SizeUnits toUnit
)
```

**VB**<br />
``` VB
Public Shared Function ConvertSize ( 
	size As Double,
	fromUnit As SizeUnits,
	toUnit As SizeUnits
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim size As Double
Dim fromUnit As SizeUnits
Dim toUnit As SizeUnits
Dim returnValue As Double

returnValue = MathUtil.ConvertSize(size, 
	fromUnit, toUnit)
```

**C++**<br />
``` C++
public:
static double ConvertSize(
	double size, 
	SizeUnits fromUnit, 
	SizeUnits toUnit
)
```

**F#**<br />
``` F#
static member ConvertSize : 
        size : float * 
        fromUnit : SizeUnits * 
        toUnit : SizeUnits -> float 

```


#### Parameters
&nbsp;<dl><dt>size</dt><dd>Type: System.Double<br />The source size to convert.</dd><dt>fromUnit</dt><dd>Type: <a href="T_DevCase_Core_IO_SizeUnits">DevCase.Core.IO.SizeUnits</a><br />From unit of size.</dd><dt>toUnit</dt><dd>Type: <a href="T_DevCase_Core_IO_SizeUnits">DevCase.Core.IO.SizeUnits</a><br />To unit of size.</dd></dl>

#### Return Value
Type: Double<br />The resulting value of the size conversion.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim byteToByte As Double = MathUtil.Convertsize(92928374, SizeUnits.Byte, SizeUnits.Byte)
Dim byteToKb As Double = MathUtil.Convertsize(92928374, SizeUnits.Byte, SizeUnits.Kilobyte)
Dim byteToMb As Double = MathUtil.Convertsize(92928374, SizeUnits.Byte, SizeUnits.Megabyte)
Console.WriteLine(String.Format("92928374 bytes = {0} Bytes", byteToByte.ToString("n0"))) ' Result: 92.928.374 Bytes
Console.WriteLine(String.Format("92928374 bytes = {0} KB", byteToKb.ToString("n2"))) ' Result: 90.750,37 KB
Console.WriteLine(String.Format("92928374 bytes = {0} MB", byteToMb.ToString("n2"))) ' Result: 88,62 MB

Dim gbToByte As Double = MathUtil.Convertsize(50, SizeUnits.Gigabyte, SizeUnits.Byte)
Dim gbToKb As Double = MathUtil.Convertsize(50, SizeUnits.Gigabyte, SizeUnits.Kilobyte)
Dim gbToMb As Double = MathUtil.Convertsize(50, SizeUnits.Gigabyte, SizeUnits.Megabyte)
Console.WriteLine(String.Format("50 GB = {0} Bytes", gbToByte.ToString("n2"))) ' Result: 53.687.091.200,00 Bytes
Console.WriteLine(String.Format("50 GB = {0} KB", gbToKb.ToString("n2"))) ' Result: 52.428.800,00 KB
Console.WriteLine(String.Format("50 GB = {0} MB", gbToMb.ToString("n2"))) ' Result: 51.200,00 MB
```


## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Tools_MathUtil">MathUtil Class</a><br /><a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools Namespace</a><br />