# DeviceUtil.GetHardDriveHandle Method (Char)
 

Gets a handle to the specified hard drive.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SafeFileHandle GetHardDriveHandle(
	char driveLetter
)
```

**VB**<br />
``` VB
Public Shared Function GetHardDriveHandle ( 
	driveLetter As Char
) As SafeFileHandle
```

**VB Usage**<br />
``` VB Usage
Dim driveLetter As Char
Dim returnValue As SafeFileHandle

returnValue = DeviceUtil.GetHardDriveHandle(driveLetter)
```

**C++**<br />
``` C++
public:
static SafeFileHandle^ GetHardDriveHandle(
	wchar_t driveLetter
)
```

**F#**<br />
``` F#
static member GetHardDriveHandle : 
        driveLetter : char -> SafeFileHandle 

```


#### Parameters
&nbsp;<dl><dt>driveLetter</dt><dd>Type: System.Char<br />The letter of the hard drive, such as "C" or "D".</dd></dl>

#### Return Value
Type: SafeFileHandle<br />A SafeFileHandle that represents the handle to the specified hard drive.

## Examples
This is a code example. 
**VB**<br />
``` VB
Using deviceHandle As SafeFileHandle = GetHardDriveHandle("C"c)
    Console.WriteLine(deviceHandle.DangerousGetHandle().ToInt32())
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_DeviceUtil">DeviceUtil Class</a><br /><a href="Overload_DevCase_Core_IO_Tools_DeviceUtil_GetHardDriveHandle">GetHardDriveHandle Overload</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />