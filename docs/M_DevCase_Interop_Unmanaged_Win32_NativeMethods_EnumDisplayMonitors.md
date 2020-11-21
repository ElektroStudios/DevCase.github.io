# NativeMethods.EnumDisplayMonitors Method 
 

Enumerates display monitors (including invisible pseudo-monitors associated with the mirroring drivers) that intersect a region formed by the intersection of a specified clipping rectangle and the visible region of a device context. 

EnumDisplayMonitors(IntPtr, IntPtr, Delegates.EnumMonitorProc, IntPtr) calls an application-defined <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumMonitorProc">Delegates.EnumMonitorProc</a> callback function once for each monitor that is enumerated. 

 Note that `GetSystemMetrics` (`SM_CMONITORS`) counts only the display monitors.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool EnumDisplayMonitors(
	IntPtr hdc,
	IntPtr lprcClip,
	Delegates.EnumMonitorProc lpfnEnum,
	IntPtr dwData
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function EnumDisplayMonitors ( 
	hdc As IntPtr,
	lprcClip As IntPtr,
	lpfnEnum As Delegates.EnumMonitorProc,
	dwData As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hdc As IntPtr
Dim lprcClip As IntPtr
Dim lpfnEnum As Delegates.EnumMonitorProc
Dim dwData As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.EnumDisplayMonitors(hdc, 
	lprcClip, lpfnEnum, dwData)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool EnumDisplayMonitors(
	IntPtr hdc, 
	IntPtr lprcClip, 
	Delegates.EnumMonitorProc^ lpfnEnum, 
	IntPtr dwData
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member EnumDisplayMonitors : 
        hdc : IntPtr * 
        lprcClip : IntPtr * 
        lpfnEnum : Delegates.EnumMonitorProc * 
        dwData : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.IntPtr<br />A handle to a display device context that defines the visible region of interest. 

 If this parameter is Zero, the `hdcMonitor` parameter passed to the <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumMonitorProc">Delegates.EnumMonitorProc</a> function will be Zero, and the visible region of interest is the virtual screen that encompasses all the displays on the desktop.</dd><dt>lprcClip</dt><dd>Type: System.IntPtr<br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that specifies a clipping rectangle. 

 The region of interest is the intersection of the clipping rectangle with the visible region specified by hdc. 

 If *hdc* is not Zero, the coordinates of the clipping rectangle are relative to the origin of the *hdc*. 

 If *hdc* is Zero, the coordinates are virtual-screen coordinates. 

 This parameter can be Zero if you don't want to clip the region specified by *hdc*.</dd><dt>lpfnEnum</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumMonitorProc">DevCase.Interop.Unmanaged.Win32.Delegates.EnumMonitorProc</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumMonitorProc">Delegates.EnumMonitorProc</a> application-defined callback function..</dd><dt>dwData</dt><dd>Type: System.IntPtr<br />Application-defined data that EnumDisplayMonitors(IntPtr, IntPtr, Delegates.EnumMonitorProc, IntPtr) passes directly to the <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumMonitorProc">Delegates.EnumMonitorProc</a> function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/dd162610%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/dd162610%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />