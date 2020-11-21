# NativeMethods.MonitorFromRect Method (Rectangle, MonitorFromFlags)
 

Retrieves a handle to the display monitor that has the largest area of intersection with a specified rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr MonitorFromRect(
	in Rectangle refRect,
	MonitorFromFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function MonitorFromRect ( 
	ByRef refRect As Rectangle,
	flags As MonitorFromFlags
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim refRect As Rectangle
Dim flags As MonitorFromFlags
Dim returnValue As IntPtr

returnValue = NativeMethods.MonitorFromRect(refRect, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr MonitorFromRect(
	[InAttribute] Rectangle% refRect, 
	MonitorFromFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member MonitorFromRect : 
        refRect : Rectangle byref * 
        flags : MonitorFromFlags -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A Rectangle structure that specifies the rectangle of interest in virtual-screen coordinates.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MonitorFromFlags">DevCase.Interop.Unmanaged.Win32.Enums.MonitorFromFlags</a><br />Determines the function's return value if the rectangle does not intersect any display monitor</dd></dl>

#### Return Value
Type: IntPtr<br />If the rectangle intersects one or more display monitor rectangles, the return value is an HMONITOR handle to the display monitor that has the largest area of intersection with the rectangle. 

 If the rectangle does not intersect a display monitor, the return value depends on the value of *flags*.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-monitorfromrect" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-monitorfromrect</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_MonitorFromRect">MonitorFromRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />