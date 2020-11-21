# Delegates.EnumMonitorProc Delegate
 

An application-defined callback function that is called by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDisplayMonitors">EnumDisplayMonitors(IntPtr, IntPtr, Delegates.EnumMonitorProc, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate bool EnumMonitorProc(
	IntPtr hMonitor,
	IntPtr hdcMonitor,
	ref NativeRectangle refMonitorRect,
	IntPtr data
)
```

**VB**<br />
``` VB
Public Delegate Function EnumMonitorProc ( 
	hMonitor As IntPtr,
	hdcMonitor As IntPtr,
	ByRef refMonitorRect As NativeRectangle,
	data As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As New EnumMonitorProc(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate bool EnumMonitorProc(
	IntPtr hMonitor, 
	IntPtr hdcMonitor, 
	NativeRectangle% refMonitorRect, 
	IntPtr data
)
```

**F#**<br />
``` F#
type EnumMonitorProc = 
    delegate of 
        hMonitor : IntPtr * 
        hdcMonitor : IntPtr * 
        refMonitorRect : NativeRectangle byref * 
        data : IntPtr -> bool
```


#### Parameters
&nbsp;<dl><dt>hMonitor</dt><dd>Type: System.IntPtr<br />A handle to the display monitor. This value will always be non-NULL.</dd><dt>hdcMonitor</dt><dd>Type: System.IntPtr<br />A handle to a device context. 

 The device context has color attributes that are appropriate for the display monitor identified by *hMonitor*. 

 The clipping area of the device context is set to the intersection of the visible region of the device context identified by the `hdc` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDisplayMonitors">EnumDisplayMonitors(IntPtr, IntPtr, Delegates.EnumMonitorProc, IntPtr)</a>, the rectangle pointed to by the `lprcClip` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDisplayMonitors">EnumDisplayMonitors(IntPtr, IntPtr, Delegates.EnumMonitorProc, IntPtr)</a>, and the display monitor rectangle. 

 This value is Zero if the `hdc` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDisplayMonitors">EnumDisplayMonitors(IntPtr, IntPtr, Delegates.EnumMonitorProc, IntPtr)</a> was Zero.</dd><dt>refMonitorRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure. 

 If hdcMonitor is not Zero, this rectangle is the intersection of the clipping area of the device context identified by *hdcMonitor* and the display monitor rectangle. 

 The rectangle coordinates are device-context coordinates. 

 If *hdcMonitor* is Zero, this rectangle is the display monitor rectangle. 

 The rectangle coordinates are virtual-screen coordinates.</dd><dt>data</dt><dd>Type: System.IntPtr<br />Application-defined data that <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDisplayMonitors">EnumDisplayMonitors(IntPtr, IntPtr, Delegates.EnumMonitorProc, IntPtr)</a> passes directly to the enumeration function.</dd></dl>

#### Return Value
Type: Boolean<br />To continue enumeration, the callback function must return `true` (`True` in Visual Basic); to stop enumeration, it must return `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/dd145061%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/dd145061%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />