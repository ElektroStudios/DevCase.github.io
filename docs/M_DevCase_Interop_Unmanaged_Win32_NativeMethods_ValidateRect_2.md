# NativeMethods.ValidateRect Method (SafeHandle, NativeRectangle)
 

Validates the client area within a rectangle by removing the rectangle from the update region of the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool ValidateRect(
	SafeHandle hWnd,
	ref NativeRectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function ValidateRect ( 
	hWnd As SafeHandle,
	ByRef refRect As NativeRectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim refRect As NativeRectangle
Dim returnValue As Boolean

returnValue = NativeMethods.ValidateRect(hWnd, 
	refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool ValidateRect(
	SafeHandle^ hWnd, 
	NativeRectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member ValidateRect : 
        hWnd : SafeHandle * 
        refRect : NativeRectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window whose update region is to be modified. 

 If this parameter is Zero, the system invalidates and redraws all windows and sends the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_EraseBkgnd</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcPaint</a> messages to the window procedure before the function returns.</dd><dt>refRect</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that contains the client coordinates of the rectangle to be removed from the update region. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the entire client area is removed.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-validaterect" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-validaterect</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ValidateRect">ValidateRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />