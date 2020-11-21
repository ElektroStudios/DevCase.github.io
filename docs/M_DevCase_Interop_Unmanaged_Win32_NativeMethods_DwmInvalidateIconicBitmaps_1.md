# NativeMethods.DwmInvalidateIconicBitmaps Method (SafeHandle)
 

Called by an application to indicate that all previously provided iconic bitmaps from a window, both thumbnails and peek representations, should be refreshed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll")]
public static int DwmInvalidateIconicBitmaps(
	SafeHandle hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll">]
Public Shared Function DwmInvalidateIconicBitmaps ( 
	hWnd As SafeHandle
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim returnValue As Integer

returnValue = NativeMethods.DwmInvalidateIconicBitmaps(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll")]
static int DwmInvalidateIconicBitmaps(
	SafeHandle^ hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll")>]
static member DwmInvalidateIconicBitmaps : 
        hWnd : SafeHandle -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the window or tab whose bitmaps are being invalidated through this call 

 This window must belong To the calling process.</dd></dl>

#### Return Value
Type: Int32<br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd389409%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd389409%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DwmInvalidateIconicBitmaps">DwmInvalidateIconicBitmaps Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />