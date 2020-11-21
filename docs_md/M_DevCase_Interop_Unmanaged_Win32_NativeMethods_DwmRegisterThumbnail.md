# NativeMethods.DwmRegisterThumbnail Method 
 

Creates a Desktop Window Manager (DWM) thumbnail relationship between the destination and source windows.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll", SetLastError = true)]
public static HResult DwmRegisterThumbnail(
	IntPtr dstHwnd,
	IntPtr srcHwnd,
	ref IntPtr refThumbnailId
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll", SetLastError := true>]
Public Shared Function DwmRegisterThumbnail ( 
	dstHwnd As IntPtr,
	srcHwnd As IntPtr,
	ByRef refThumbnailId As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim dstHwnd As IntPtr
Dim srcHwnd As IntPtr
Dim refThumbnailId As IntPtr
Dim returnValue As HResult

returnValue = NativeMethods.DwmRegisterThumbnail(dstHwnd, 
	srcHwnd, refThumbnailId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll", SetLastError = true)]
static HResult DwmRegisterThumbnail(
	IntPtr dstHwnd, 
	IntPtr srcHwnd, 
	IntPtr% refThumbnailId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll", SetLastError = true)>]
static member DwmRegisterThumbnail : 
        dstHwnd : IntPtr * 
        srcHwnd : IntPtr * 
        refThumbnailId : IntPtr byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>dstHwnd</dt><dd>Type: System.IntPtr<br />The handle to the window that will use the DWM thumbnail. 

 Setting the destination window handle to anything other than a top-level window type will result in a return value of <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_INVALIDARG</a>.</dd><dt>srcHwnd</dt><dd>Type: System.IntPtr<br />The handle to the window to use as the thumbnail source. 

 Setting the source window handle to anything other than a top-level window type will result in a return value of <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_INVALIDARG</a>.</dd><dt>refThumbnailId</dt><dd>Type: System.IntPtr<br />A pointer to a handle that, when this function returns successfully, represents the registration of the DWM thumbnail.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmregisterthumbnail" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmregisterthumbnail</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />