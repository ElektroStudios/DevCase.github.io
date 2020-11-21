# MathUtil.ConvertSizeToDiscStorage Method 
 

Converts a size to a disc-storage size.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static double ConvertSizeToDiscStorage(
	double size,
	SizeUnits fromSizeUnit,
	DiscType toDiscType
)
```

**VB**<br />
``` VB
Public Shared Function ConvertSizeToDiscStorage ( 
	size As Double,
	fromSizeUnit As SizeUnits,
	toDiscType As DiscType
) As Double
```

**VB Usage**<br />
``` VB Usage
Dim size As Double
Dim fromSizeUnit As SizeUnits
Dim toDiscType As DiscType
Dim returnValue As Double

returnValue = MathUtil.ConvertSizeToDiscStorage(size, 
	fromSizeUnit, toDiscType)
```

**C++**<br />
``` C++
public:
static double ConvertSizeToDiscStorage(
	double size, 
	SizeUnits fromSizeUnit, 
	DiscType toDiscType
)
```

**F#**<br />
``` F#
static member ConvertSizeToDiscStorage : 
        size : float * 
        fromSizeUnit : SizeUnits * 
        toDiscType : DiscType -> float 

```


#### Parameters
&nbsp;<dl><dt>size</dt><dd>Type: System.Double<br />The source size to convert.</dd><dt>fromSizeUnit</dt><dd>Type: <a href="T_DevCase_Core_IO_SizeUnits">DevCase.Core.IO.SizeUnits</a><br />From unit of size.</dd><dt>toDiscType</dt><dd>Type: <a href="T_DevCase_Core_IO_DiscType">DevCase.Core.IO.DiscType</a><br />To disc-storage size.</dd></dl>

#### Return Value
Type: Double<br />The resulting value of the size conversion.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim size As Double = 6.5 ' Gigabytes.
Dim dvdSize As Double = ConvertSizeToDiscStorage(6.5, SizeUnits.Gigabyte, DiscType.Dvd)
Console.WriteLine(String.Format("To write {0} GB you need to burn {1} DVDs.", size, Math.Ceiling(dvdSize)))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Tools_MathUtil">MathUtil Class</a><br /><a href="N_DevCase_Core_Maths_Tools">DevCase.Core.Maths.Tools Namespace</a><br />