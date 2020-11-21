# NativeMethods.GetMonitorInfo Method (IntPtr, MonitorInfoEx)
 

Retrieves information about a display monitor.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool GetMonitorInfo(
	IntPtr hWnd,
	ref MonitorInfoEx mi
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetMonitorInfo ( 
	hWnd As IntPtr,
	ByRef mi As MonitorInfoEx
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim mi As MonitorInfoEx
Dim returnValue As Boolean

returnValue = NativeMethods.GetMonitorInfo(hWnd, 
	mi)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool GetMonitorInfo(
	IntPtr hWnd, 
	MonitorInfoEx% mi
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetMonitorInfo : 
        hWnd : IntPtr * 
        mi : MonitorInfoEx byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the display monitor of interest.</dd><dt>mi</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx">DevCase.Interop.Unmanaged.Win32.Structures.MonitorInfoEx</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx">MonitorInfoEx</a> structure that receives information about the specified display monitor. 

 You must set the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_SizeOfStruct">SizeOfStruct</a> member of the structure to `Marshal.SizeOf(Of MonitorInfoEx)` before calling the GetMonitorInfo function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd144901(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd144901(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMonitorInfo">GetMonitorInfo Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />