# NativeMethods.InvalidateRect Method (IntPtr, Rectangle, Boolean)
 

Adds a rectangle to the specified window's update region. 

 The update region represents the portion of the window's client area that must be redrawn.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool InvalidateRect(
	IntPtr hWnd,
	ref Rectangle refRect,
	bool erase
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function InvalidateRect ( 
	hWnd As IntPtr,
	ByRef refRect As Rectangle,
	erase As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim refRect As Rectangle
Dim erase As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.InvalidateRect(hWnd, 
	refRect, erase)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool InvalidateRect(
	IntPtr hWnd, 
	Rectangle% refRect, 
	bool erase
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member InvalidateRect : 
        hWnd : IntPtr * 
        refRect : Rectangle byref * 
        erase : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window whose update region has changed. 

 If this parameter is Zero, the system invalidates and redraws all windows, not just the windows for this application, and sends the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_EraseBkgnd</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcPaint</a> messages before the function returns. 

 Setting this parameter to Zero is not recommended.</dd><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A Rectangle structure that contains the client coordinates of the rectangle to be added to the update region. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the entire client area is added to the update region.</dd><dt>erase</dt><dd>Type: System.Boolean<br />\[Missing <param name="erase"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.InvalidateRect(System.IntPtr,System.Drawing.Rectangle@,System.Boolean)"\]</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-invalidaterect" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-invalidaterect</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_InvalidateRect">InvalidateRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />