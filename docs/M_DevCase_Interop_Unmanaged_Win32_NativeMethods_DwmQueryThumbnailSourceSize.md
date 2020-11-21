# NativeMethods.DwmQueryThumbnailSourceSize Method 
 

Retrieves the source size of the Desktop Window Manager (DWM) thumbnail.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll", SetLastError = true)]
public static HResult DwmQueryThumbnailSourceSize(
	IntPtr thumbnailId,
	out NativeSize refSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll", SetLastError := true>]
Public Shared Function DwmQueryThumbnailSourceSize ( 
	thumbnailId As IntPtr,
	<OutAttribute> ByRef refSize As NativeSize
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim thumbnailId As IntPtr
Dim refSize As NativeSize
Dim returnValue As HResult

returnValue = NativeMethods.DwmQueryThumbnailSourceSize(thumbnailId, 
	refSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll", SetLastError = true)]
static HResult DwmQueryThumbnailSourceSize(
	IntPtr thumbnailId, 
	[OutAttribute] NativeSize% refSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll", SetLastError = true)>]
static member DwmQueryThumbnailSourceSize : 
        thumbnailId : IntPtr * 
        refSize : NativeSize byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>thumbnailId</dt><dd>Type: System.IntPtr<br />A handle to the thumbnail to retrieve the source window size from.</dd><dt>refSize</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">DevCase.Interop.Unmanaged.Win32.Structures.NativeSize</a><br />A pointer to a NativeSize structure that, when this function returns successfully, receives the size of the source thumbnail.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmquerythumbnailsourcesize" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmquerythumbnailsourcesize</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />