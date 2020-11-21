# NativeMethods.MonitorFromWindow Method (IntPtr, MonitorFromFlags)
 

Retrieves a handle to the display monitor that has the largest area of intersection with the bounding rectangle of a specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr MonitorFromWindow(
	IntPtr hWnd,
	MonitorFromFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function MonitorFromWindow ( 
	hWnd As IntPtr,
	flags As MonitorFromFlags
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim flags As MonitorFromFlags
Dim returnValue As IntPtr

returnValue = NativeMethods.MonitorFromWindow(hWnd, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr MonitorFromWindow(
	IntPtr hWnd, 
	MonitorFromFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member MonitorFromWindow : 
        hWnd : IntPtr * 
        flags : MonitorFromFlags -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window whose parent monitor handle is to be retrieved.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MonitorFromFlags">DevCase.Interop.Unmanaged.Win32.Enums.MonitorFromFlags</a><br />Determines the function's return value if the window does not intersect any display monitor.</dd></dl>

#### Return Value
Type: IntPtr<br />If the window intersects one or more display monitor rectangles, the return value is an `HMONITOR` handle to the display monitor that has the largest area of intersection with the window. 

 If the window does not intersect a display monitor, the return value depends on the value of *flags* parameters.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd145064%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd145064%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_MonitorFromWindow">MonitorFromWindow Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />