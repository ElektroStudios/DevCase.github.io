# Filesize.Size Property (SizeUnits)
 

Gets the filesize, in the specified unit of size.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public double this[
	SizeUnits sizeUnit
] { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Size ( 
	sizeUnit As SizeUnits
) As Double
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As Filesize
Dim sizeUnit As SizeUnits
Dim value As Double

value = instance.Size(sizeUnit)

```

**C++**<br />
``` C++
public:
property double Size[SizeUnits sizeUnit] {
	double get (SizeUnits sizeUnit);
}
```

**F#**<br />
``` F#
member Size : float with get

```


#### Parameters
&nbsp;<dl><dt>sizeUnit</dt><dd>Type: <a href="T_DevCase_Core_IO_SizeUnits">DevCase.Core.IO.SizeUnits</a><br />The unit of size.</dd></dl>

#### Property Value
Type: Double<br />The filesize.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Filesize">Filesize Class</a><br /><a href="Overload_DevCase_Core_IO_Filesize_Size">Size Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />