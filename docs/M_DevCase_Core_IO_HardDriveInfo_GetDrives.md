# HardDriveInfo.GetDrives Method 
 

Gets all the hard drives of the current machine.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<HardDriveInfo> GetDrives()
```

**VB**<br />
``` VB
Public Shared Function GetDrives As IEnumerable(Of HardDriveInfo)
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IEnumerable(Of HardDriveInfo)

returnValue = HardDriveInfo.GetDrives()
```

**C++**<br />
``` C++
public:
static IEnumerable<HardDriveInfo^>^ GetDrives()
```

**F#**<br />
``` F#
static member GetDrives : unit -> IEnumerable<HardDriveInfo> 

```


#### Return Value
Type: IEnumerable(<a href="T_DevCase_Core_IO_HardDriveInfo">HardDriveInfo</a>)<br />An IEnumerable(T) that contains all the hard drives of the current machine.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_HardDriveInfo">HardDriveInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />