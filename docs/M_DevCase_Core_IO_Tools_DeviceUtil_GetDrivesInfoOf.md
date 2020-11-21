# DeviceUtil.GetDrivesInfoOf Method 
 

Gets all the drives of the specified DriveType.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<DriveInfo> GetDrivesInfoOf(
	DriveType driveType
)
```

**VB**<br />
``` VB
Public Shared Function GetDrivesInfoOf ( 
	driveType As DriveType
) As IEnumerable(Of DriveInfo)
```

**VB Usage**<br />
``` VB Usage
Dim driveType As DriveType
Dim returnValue As IEnumerable(Of DriveInfo)

returnValue = DeviceUtil.GetDrivesInfoOf(driveType)
```

**C++**<br />
``` C++
public:
static IEnumerable<DriveInfo^>^ GetDrivesInfoOf(
	DriveType driveType
)
```

**F#**<br />
``` F#
static member GetDrivesInfoOf : 
        driveType : DriveType -> IEnumerable<DriveInfo> 

```


#### Parameters
&nbsp;<dl><dt>driveType</dt><dd>Type: System.IO.DriveType<br />The type of drive.</dd></dl>

#### Return Value
Type: IEnumerable(DriveInfo)<br />An IEnumerable(T) that contains all the drives of specified type.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hardDrives As IEnumerable(Of DriveInfo) = GetDrivesInfoOf(DriveType.Fixed)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />