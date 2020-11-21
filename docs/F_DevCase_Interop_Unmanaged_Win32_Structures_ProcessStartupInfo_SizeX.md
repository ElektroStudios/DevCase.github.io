# ProcessStartupInfo.SizeX Field
 

If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseSize</a>, this member is the width of the window if a new window is created, in pixels. Otherwise, this member is ignored. 

 For GUI processes, this is used only the first time the new process calls CreateWindow to create an overlapped window if the nWidth parameter of CreateWindow is CW_USEDEFAULT.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int SizeX
```

**VB**<br />
``` VB
Public SizeX As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessStartupInfo
Dim value As Integer

value = instance.SizeX

instance.SizeX = value
```

**C++**<br />
``` C++
public:
int SizeX
```

**F#**<br />
``` F#
val mutable SizeX: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo">ProcessStartupInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />