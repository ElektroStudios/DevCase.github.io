# ProcessStartupInfo.StdInput Field
 

If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseStdHandles</a>, this member is the standard input handle for the process. 

 If <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseStdHandles</a> is not specified, the default for standard input is the keyboard buffer. 

 If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseHotkey</a>, this member specifies a hotkey value that is sent as the wParam parameter of a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SetHotkey</a> message to the first eligible top-level window created by the application that owns the process. If the window is created with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowStyles">Popup</a> window style, it is not eligible unless the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowStylesEx">AppWindow</a> extended window style is also set.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int StdInput
```

**VB**<br />
``` VB
Public StdInput As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessStartupInfo
Dim value As Integer

value = instance.StdInput

instance.StdInput = value
```

**C++**<br />
``` C++
public:
int StdInput
```

**F#**<br />
``` F#
val mutable StdInput: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo">ProcessStartupInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />