# NativeMethods.DwmUpdateThumbnailProperties Method 
 

Updates the properties for a Desktop Window Manager (DWM) thumbnail.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll", SetLastError = true)]
public static HResult DwmUpdateThumbnailProperties(
	IntPtr thumbnailId,
	ref DwmThumbnailProperties refThumbnailProperties
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll", SetLastError := true>]
Public Shared Function DwmUpdateThumbnailProperties ( 
	thumbnailId As IntPtr,
	ByRef refThumbnailProperties As DwmThumbnailProperties
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim thumbnailId As IntPtr
Dim refThumbnailProperties As DwmThumbnailProperties
Dim returnValue As HResult

returnValue = NativeMethods.DwmUpdateThumbnailProperties(thumbnailId, 
	refThumbnailProperties)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll", SetLastError = true)]
static HResult DwmUpdateThumbnailProperties(
	IntPtr thumbnailId, 
	DwmThumbnailProperties% refThumbnailProperties
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll", SetLastError = true)>]
static member DwmUpdateThumbnailProperties : 
        thumbnailId : IntPtr * 
        refThumbnailProperties : DwmThumbnailProperties byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>thumbnailId</dt><dd>Type: System.IntPtr<br />The handle to the DWM thumbnail to be updated. 

 A value of Zero or invalid thumbnail handles, as well as thumbnails owned by other processes will result in a return value of <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_INVALIDARG</a>.</dd><dt>refThumbnailProperties</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DwmThumbnailProperties">DevCase.Interop.Unmanaged.Win32.Structures.DwmThumbnailProperties</a><br />A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DwmThumbnailProperties">DwmThumbnailProperties</a> structure that contains the new thumbnail properties.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmupdatethumbnailproperties" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmupdatethumbnailproperties</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />