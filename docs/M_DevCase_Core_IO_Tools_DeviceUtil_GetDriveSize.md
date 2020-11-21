# DeviceUtil.GetDriveSize Method 
 

Gets the total size, in bytes, of the specified drive.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static long GetDriveSize(
	char driveLetter
)
```

**VB**<br />
``` VB
Public Shared Function GetDriveSize ( 
	driveLetter As Char
) As Long
```

**VB Usage**<br />
``` VB Usage
Dim driveLetter As Char
Dim returnValue As Long

returnValue = DeviceUtil.GetDriveSize(driveLetter)
```

**C++**<br />
``` C++
public:
static long long GetDriveSize(
	wchar_t driveLetter
)
```

**F#**<br />
``` F#
static member GetDriveSize : 
        driveLetter : char -> int64 

```


#### Parameters
&nbsp;<dl><dt>driveLetter</dt><dd>Type: System.Char<br />The drive letter.</dd></dl>

#### Return Value
Type: Int64<br />The disk size, in bytes.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>DriveNotFoundException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim driveSize As String = String.Format("{0} GB", (GetDriveSize("C"c) / (1024 ^ 3)).ToString("n2"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />