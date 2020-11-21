# ProcessStartupInfo.ShowWindow Field
 

If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseShowWindow</a>, this member can be any of the values that can be specified in the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">NativeWindowState</a> enumeration, except for <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">ShowDefault</a>. Otherwise, this member is ignored. 

 For GUI processes, the first time ShowWindow is called, its nCmdShow parameter is ignored ShowWindow specifies the default value. In subsequent calls to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ShowWindow">ShowWindow(IntPtr, NativeWindowState)</a>, the ShowWindow member is used if the nCmdShow parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ShowWindow">ShowWindow(IntPtr, NativeWindowState)</a> is set to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">ShowDefault</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public NativeWindowState ShowWindow
```

**VB**<br />
``` VB
Public ShowWindow As NativeWindowState
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessStartupInfo
Dim value As NativeWindowState

value = instance.ShowWindow

instance.ShowWindow = value
```

**C++**<br />
``` C++
public:
NativeWindowState ShowWindow
```

**F#**<br />
``` F#
val mutable ShowWindow: NativeWindowState
```


#### Field Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">NativeWindowState</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo">ProcessStartupInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />