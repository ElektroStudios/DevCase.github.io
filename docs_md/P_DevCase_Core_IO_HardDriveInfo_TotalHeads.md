# HardDriveInfo.TotalHeads Property 
 

Gets the total number of heads on the hard drive. 

 Note: the value for this property is obtained through extended functions of BIOS interrupt 13h. 

 The value may be inaccurate if the drive uses a translation scheme to support high-capacity disk sizes. 

 Consult the manufacturer for accurate drive specifications.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int TotalHeads { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property TotalHeads As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As HardDriveInfo
Dim value As Integer

value = instance.TotalHeads

```

**C++**<br />
``` C++
public:
property int TotalHeads {
	int get ();
}
```

**F#**<br />
``` F#
member TotalHeads : int with get

```


#### Property Value
Type: Int32<br />\[Missing <value> documentation for "P:DevCase.Core.IO.HardDriveInfo.TotalHeads"\]

## See Also


#### Reference
<a href="T_DevCase_Core_IO_HardDriveInfo">HardDriveInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />