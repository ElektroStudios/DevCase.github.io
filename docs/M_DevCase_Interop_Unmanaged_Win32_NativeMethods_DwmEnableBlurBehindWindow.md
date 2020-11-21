# NativeMethods.DwmEnableBlurBehindWindow Method 
 

Enables the blur effect on a specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll")]
[SecurityCriticalAttribute]
public static HResult DwmEnableBlurBehindWindow(
	IntPtr hWnd,
	ref DwmBlurBehind refDwmBlurBehind
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll">]
<SecurityCriticalAttribute>
Public Shared Function DwmEnableBlurBehindWindow ( 
	hWnd As IntPtr,
	ByRef refDwmBlurBehind As DwmBlurBehind
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim refDwmBlurBehind As DwmBlurBehind
Dim returnValue As HResult

returnValue = NativeMethods.DwmEnableBlurBehindWindow(hWnd, 
	refDwmBlurBehind)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll")]
[SecurityCriticalAttribute]
static HResult DwmEnableBlurBehindWindow(
	IntPtr hWnd, 
	DwmBlurBehind% refDwmBlurBehind
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll")>]
[<SecurityCriticalAttribute>]
static member DwmEnableBlurBehindWindow : 
        hWnd : IntPtr * 
        refDwmBlurBehind : DwmBlurBehind byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />The handle to the window on which the blur behind data is applied.</dd><dt>refDwmBlurBehind</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DwmBlurBehind">DevCase.Interop.Unmanaged.Win32.Structures.DwmBlurBehind</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DwmBlurBehind">DwmBlurBehind</a> structure that provides blur behind data.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmenableblurbehindwindow" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmenableblurbehindwindow</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />