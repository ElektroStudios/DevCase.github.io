# Filesize Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_Filesize">Filesize</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Filesize(
	double size,
	SizeUnits sizeUnit
)
```

**VB**<br />
``` VB
Public Sub New ( 
	size As Double,
	sizeUnit As SizeUnits
)
```

**VB Usage**<br />
``` VB Usage
Dim size As Double
Dim sizeUnit As SizeUnits

Dim instance As New Filesize(size, sizeUnit)
```

**C++**<br />
``` C++
public:
Filesize(
	double size, 
	SizeUnits sizeUnit
)
```

**F#**<br />
``` F#
new : 
        size : float * 
        sizeUnit : SizeUnits -> Filesize
```


#### Parameters
&nbsp;<dl><dt>size</dt><dd>Type: System.Double<br />The filesize.</dd><dt>sizeUnit</dt><dd>Type: <a href="T_DevCase_Core_IO_SizeUnits">DevCase.Core.IO.SizeUnits</a><br />The unit of size.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Filesize">Filesize Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />