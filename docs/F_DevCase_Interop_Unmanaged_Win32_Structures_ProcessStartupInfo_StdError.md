# ProcessStartupInfo.StdError Field
 

If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseStdHandles</a>, this member is the standard error handle for the process. Otherwise, this member is ignored and the default for standard error is the console window's buffer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int StdError
```

**VB**<br />
``` VB
Public StdError As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessStartupInfo
Dim value As Integer

value = instance.StdError

instance.StdError = value
```

**C++**<br />
``` C++
public:
int StdError
```

**F#**<br />
``` F#
val mutable StdError: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo">ProcessStartupInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />