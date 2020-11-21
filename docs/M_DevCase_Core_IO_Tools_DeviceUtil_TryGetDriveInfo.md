# DeviceUtil.TryGetDriveInfo Method 
 

Tries to get the corresponding DriveInfo for the specified drive letter.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool TryGetDriveInfo(
	char driveLetter,
	ref DriveInfo refDriveInfo
)
```

**VB**<br />
``` VB
Public Shared Function TryGetDriveInfo ( 
	driveLetter As Char,
	ByRef refDriveInfo As DriveInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim driveLetter As Char
Dim refDriveInfo As DriveInfo
Dim returnValue As Boolean

returnValue = DeviceUtil.TryGetDriveInfo(driveLetter, 
	refDriveInfo)
```

**C++**<br />
``` C++
public:
static bool TryGetDriveInfo(
	wchar_t driveLetter, 
	DriveInfo^% refDriveInfo
)
```

**F#**<br />
``` F#
static member TryGetDriveInfo : 
        driveLetter : char * 
        refDriveInfo : DriveInfo byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>driveLetter</dt><dd>Type: System.Char<br />The drive letter, such as "C" or "D".</dd><dt>refDriveInfo</dt><dd>Type: System.IO.DriveInfo<br />If this function returns successfully, *refDriveInfo* contains the resulting DriveInfo. 

 If this function returns unsuccessfully, *refDriveInfo* is null.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if successful; `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim driveInfo As DriveInfo 
Dim result As Boolean = TryGetDriveInfo("C"c, driveInfo)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />