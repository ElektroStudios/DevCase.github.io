# HardDriveInfo Constructor (DriveInfo)
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_HardDriveInfo">HardDriveInfo</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public HardDriveInfo(
	DriveInfo driveInfo
)
```

**VB**<br />
``` VB
Public Sub New ( 
	driveInfo As DriveInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim driveInfo As DriveInfo

Dim instance As New HardDriveInfo(driveInfo)
```

**C++**<br />
``` C++
public:
HardDriveInfo(
	DriveInfo^ driveInfo
)
```

**F#**<br />
``` F#
new : 
        driveInfo : DriveInfo -> HardDriveInfo
```


#### Parameters
&nbsp;<dl><dt>driveInfo</dt><dd>Type: System.IO.DriveInfo<br />A DriveInfo instance that represents the hard drive.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>The specified drive is not a hard drive.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_HardDriveInfo">HardDriveInfo Class</a><br /><a href="Overload_DevCase_Core_IO_HardDriveInfo__ctor">HardDriveInfo Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />