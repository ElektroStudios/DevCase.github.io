# NativeMethods.ValidateRgn Method (SafeHandle, SafeHandle)
 

Validates the client area within a region by removing the region from the current update region of the specified window..

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool ValidateRgn(
	SafeHandle hWnd,
	SafeHandle hRgn
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function ValidateRgn ( 
	hWnd As SafeHandle,
	hRgn As SafeHandle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim hRgn As SafeHandle
Dim returnValue As Boolean

returnValue = NativeMethods.ValidateRgn(hWnd, 
	hRgn)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool ValidateRgn(
	SafeHandle^ hWnd, 
	SafeHandle^ hRgn
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member ValidateRgn : 
        hWnd : SafeHandle * 
        hRgn : SafeHandle -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window whose update region is to be modified.</dd><dt>hRgn</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to a region that defines the area to be removed from the update region. 

 If this parameter is Zero, the entire client area is removed.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-validatergn" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-validatergn</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ValidateRgn">ValidateRgn Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />