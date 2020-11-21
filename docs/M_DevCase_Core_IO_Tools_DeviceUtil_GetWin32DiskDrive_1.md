# DeviceUtil.GetWin32DiskDrive Method (DriveInfo)
 

Gets a ManagementObject which wraps a instance of 'Win32_DiskDrive' WMI class for the specified drive.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ManagementObject GetWin32DiskDrive(
	DriveInfo driveInfo
)
```

**VB**<br />
``` VB
Public Shared Function GetWin32DiskDrive ( 
	driveInfo As DriveInfo
) As ManagementObject
```

**VB Usage**<br />
``` VB Usage
Dim driveInfo As DriveInfo
Dim returnValue As ManagementObject

returnValue = DeviceUtil.GetWin32DiskDrive(driveInfo)
```

**C++**<br />
``` C++
public:
static ManagementObject^ GetWin32DiskDrive(
	DriveInfo^ driveInfo
)
```

**F#**<br />
``` F#
static member GetWin32DiskDrive : 
        driveInfo : DriveInfo -> ManagementObject 

```


#### Parameters
&nbsp;<dl><dt>driveInfo</dt><dd>Type: System.IO.DriveInfo<br />A DriveInfo instance that represents the drive.</dd></dl>

#### Return Value
Type: ManagementObject<br />A ManagementObject which wraps a instance of 'Win32_DiskDrive' WMI class for the specified drive.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim driveInfo As DriveInfo = My.Computer.FileSystem.GetDriveInfo("C"c)
Using win32DiskDrive As ManagementObject = GetWin32DiskDrive(driveInfo)
    Console.WriteLine(win32DiskDrive.GetPropertyValue("Name").ToString())
    Console.WriteLine(win32DiskDrive.GetPropertyValue("Model").ToString())
    Console.WriteLine(win32DiskDrive.GetPropertyValue("SerialNumber").ToString())
    Console.WriteLine(win32DiskDrive.GetPropertyValue("DeviceID").ToString())
    Console.WriteLine(win32DiskDrive.GetPropertyValue("PNPDeviceID").ToString())
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DeviceUtil_GetWin32DiskDrive">GetWin32DiskDrive Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />