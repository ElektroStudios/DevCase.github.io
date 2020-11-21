# ProcessStartupInfo.CountCharsX Field
 

If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseCountChars</a>, if a new console window is created in a console process, this member specifies the screen buffer width, in character columns. Otherwise, this member is ignored..

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int CountCharsX
```

**VB**<br />
``` VB
Public CountCharsX As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessStartupInfo
Dim value As Integer

value = instance.CountCharsX

instance.CountCharsX = value
```

**C++**<br />
``` C++
public:
int CountCharsX
```

**F#**<br />
``` F#
val mutable CountCharsX: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo">ProcessStartupInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />