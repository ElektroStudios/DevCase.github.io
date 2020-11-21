# NativeMethods.InvalidateRgn Method (SafeHandle, SafeHandle, Boolean)
 

Invalidates the client area within the specified region by adding it to the current update region of a window. 

 The invalidated region, along with all other areas in the update region, is marked for painting when the next <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Paint</a> message occurs.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool InvalidateRgn(
	SafeHandle hWnd,
	SafeHandle hRgn,
	bool erase
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function InvalidateRgn ( 
	hWnd As SafeHandle,
	hRgn As SafeHandle,
	erase As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim hRgn As SafeHandle
Dim erase As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.InvalidateRgn(hWnd, 
	hRgn, erase)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool InvalidateRgn(
	SafeHandle^ hWnd, 
	SafeHandle^ hRgn, 
	bool erase
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member InvalidateRgn : 
        hWnd : SafeHandle * 
        hRgn : SafeHandle * 
        erase : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window with an update region that is to be modified.</dd><dt>hRgn</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the region to be added to the update region. 

 The region is assumed to have client coordinates. 

 If this parameter is Zero, the entire client area is added to the update region.</dd><dt>erase</dt><dd>Type: System.Boolean<br />\[Missing <param name="erase"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.InvalidateRgn(System.Runtime.InteropServices.SafeHandle,System.Runtime.InteropServices.SafeHandle,System.Boolean)"\]</dd></dl>

#### Return Value
Type: Boolean<br />The return value is always `true` (`True` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-invalidatergn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-invalidatergn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_InvalidateRgn">InvalidateRgn Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />