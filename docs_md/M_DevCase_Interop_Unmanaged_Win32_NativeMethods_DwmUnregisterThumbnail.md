# NativeMethods.DwmUnregisterThumbnail Method 
 

Removes a Desktop Window Manager (DWM) thumbnail relationship previously created by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DwmRegisterThumbnail">DwmRegisterThumbnail(IntPtr, IntPtr, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll", SetLastError = true)]
public static HResult DwmUnregisterThumbnail(
	IntPtr thumbnailId
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll", SetLastError := true>]
Public Shared Function DwmUnregisterThumbnail ( 
	thumbnailId As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim thumbnailId As IntPtr
Dim returnValue As HResult

returnValue = NativeMethods.DwmUnregisterThumbnail(thumbnailId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll", SetLastError = true)]
static HResult DwmUnregisterThumbnail(
	IntPtr thumbnailId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll", SetLastError = true)>]
static member DwmUnregisterThumbnail : 
        thumbnailId : IntPtr -> HResult 

```


#### Parameters
&nbsp;<dl><dt>thumbnailId</dt><dd>Type: System.IntPtr<br />The handle to the thumbnail relationship to be removed. 

 A value of Zero or invalid thumbnail handles will result in a return value of <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_INVALIDARG</a>.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmunregisterthumbnail" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmunregisterthumbnail</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />