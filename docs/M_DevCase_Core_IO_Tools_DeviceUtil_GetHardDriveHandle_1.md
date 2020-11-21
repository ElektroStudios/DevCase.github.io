# DeviceUtil.GetHardDriveHandle Method (DriveInfo)
 

Gets a handle to the specified hard drive.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SafeFileHandle GetHardDriveHandle(
	DriveInfo driveInfo
)
```

**VB**<br />
``` VB
Public Shared Function GetHardDriveHandle ( 
	driveInfo As DriveInfo
) As SafeFileHandle
```

**VB Usage**<br />
``` VB Usage
Dim driveInfo As DriveInfo
Dim returnValue As SafeFileHandle

returnValue = DeviceUtil.GetHardDriveHandle(driveInfo)
```

**C++**<br />
``` C++
public:
static SafeFileHandle^ GetHardDriveHandle(
	DriveInfo^ driveInfo
)
```

**F#**<br />
``` F#
static member GetHardDriveHandle : 
        driveInfo : DriveInfo -> SafeFileHandle 

```


#### Parameters
&nbsp;<dl><dt>driveInfo</dt><dd>Type: System.IO.DriveInfo<br />A DriveInfo instance that represents the hard drive.</dd></dl>

#### Return Value
Type: SafeFileHandle<br />A SafeFileHandle that represents the handle to the specified hard drive.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>The specified drive must be a hard drive.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim driveInfo As DriveInfo = My.Computer.FileSystem.GetDriveInfo("C"c)
Using deviceHandle As SafeFileHandle = GetHardDriveHandle(driveInfo)
    Console.WriteLine(deviceHandle.DangerousGetHandle().ToInt32())
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DeviceUtil_GetHardDriveHandle">GetHardDriveHandle Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />