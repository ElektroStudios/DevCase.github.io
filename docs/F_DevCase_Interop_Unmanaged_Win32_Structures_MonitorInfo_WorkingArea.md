# MonitorInfo.WorkingArea Field
 

A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that specifies the work area rectangle of the display monitor that can be used by applications, expressed in virtual-screen coordinates. 

 Windows uses this rectangle to maximize an application on the monitor. The rest of the area in <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_Bounds">Bounds</a> contains system windows such as the task bar and side bars. 

 Note that if the monitor is not the primary display monitor, some of the rectangle's coordinates may be negative values.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public NativeRectangle WorkingArea
```

**VB**<br />
``` VB
Public WorkingArea As NativeRectangle
```

**VB Usage**<br />
``` VB Usage
Dim instance As MonitorInfo
Dim value As NativeRectangle

value = instance.WorkingArea

instance.WorkingArea = value
```

**C++**<br />
``` C++
public:
NativeRectangle WorkingArea
```

**F#**<br />
``` F#
val mutable WorkingArea: NativeRectangle
```


#### Field Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfo">MonitorInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />