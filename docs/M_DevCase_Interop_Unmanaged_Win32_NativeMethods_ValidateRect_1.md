# NativeMethods.ValidateRect Method (IntPtr, Rectangle)
 

Validates the client area within a rectangle by removing the rectangle from the update region of the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool ValidateRect(
	IntPtr hWnd,
	ref Rectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function ValidateRect ( 
	hWnd As IntPtr,
	ByRef refRect As Rectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim refRect As Rectangle
Dim returnValue As Boolean

returnValue = NativeMethods.ValidateRect(hWnd, 
	refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool ValidateRect(
	IntPtr hWnd, 
	Rectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member ValidateRect : 
        hWnd : IntPtr * 
        refRect : Rectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window whose update region is to be modified. 

 If this parameter is Zero, the system invalidates and redraws all windows and sends the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_EraseBkgnd</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcPaint</a> messages to the window procedure before the function returns.</dd><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A Rectangle structure that contains the client coordinates of the rectangle to be removed from the update region. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the entire client area is removed.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-validaterect" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-validaterect</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ValidateRect">ValidateRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />