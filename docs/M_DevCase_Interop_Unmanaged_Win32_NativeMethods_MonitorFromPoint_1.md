# NativeMethods.MonitorFromPoint Method (Point, MonitorFromFlags)
 

Retrieves a handle to the display monitor that contains a specified point.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr MonitorFromPoint(
	Point pt,
	MonitorFromFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function MonitorFromPoint ( 
	pt As Point,
	flags As MonitorFromFlags
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim pt As Point
Dim flags As MonitorFromFlags
Dim returnValue As IntPtr

returnValue = NativeMethods.MonitorFromPoint(pt, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr MonitorFromPoint(
	Point pt, 
	MonitorFromFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member MonitorFromPoint : 
        pt : Point * 
        flags : MonitorFromFlags -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>pt</dt><dd>Type: System.Drawing.Point<br />A Point structure that specifies the point of interest in virtual-screen coordinates.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MonitorFromFlags">DevCase.Interop.Unmanaged.Win32.Enums.MonitorFromFlags</a><br />Determines the function's return value if the point is not contained within any display monitor</dd></dl>

#### Return Value
Type: IntPtr<br />If the point is contained by a display monitor, the return value is an HMONITOR handle to that display monitor. 

 If the point is not contained by a display monitor, the return value depends on the value of *flags*.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-monitorfrompoint" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-monitorfrompoint</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_MonitorFromPoint">MonitorFromPoint Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />