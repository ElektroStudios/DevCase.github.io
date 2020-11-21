# DeviceUtil.GetDriveInfo Method 
 

Returns the corresponding DriveInfo for the specified drive letter.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static DriveInfo GetDriveInfo(
	char driveLetter
)
```

**VB**<br />
``` VB
Public Shared Function GetDriveInfo ( 
	driveLetter As Char
) As DriveInfo
```

**VB Usage**<br />
``` VB Usage
Dim driveLetter As Char
Dim returnValue As DriveInfo

returnValue = DeviceUtil.GetDriveInfo(driveLetter)
```

**C++**<br />
``` C++
public:
static DriveInfo^ GetDriveInfo(
	wchar_t driveLetter
)
```

**F#**<br />
``` F#
static member GetDriveInfo : 
        driveLetter : char -> DriveInfo 

```


#### Parameters
&nbsp;<dl><dt>driveLetter</dt><dd>Type: System.Char<br />The drive letter, such as "C" or "D".</dd></dl>

#### Return Value
Type: DriveInfo<br />The resulting DriveInfo.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>No drive found with the specified drive letter.</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim driveInfo As DriveInfo = GetDriveInfo("C"c)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />