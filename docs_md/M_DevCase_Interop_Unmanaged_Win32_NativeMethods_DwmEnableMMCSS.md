# NativeMethods.DwmEnableMMCSS Method 
 

Notifies the Desktop Window Manager (DWM) to opt in to or out of Multimedia Class Schedule Service (MMCSS) scheduling while the calling process is alive.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll")]
public static HResult DwmEnableMMCSS(
	bool enableMMCSS
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll">]
Public Shared Function DwmEnableMMCSS ( 
	enableMMCSS As Boolean
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim enableMMCSS As Boolean
Dim returnValue As HResult

returnValue = NativeMethods.DwmEnableMMCSS(enableMMCSS)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll")]
static HResult DwmEnableMMCSS(
	bool enableMMCSS
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll")>]
static member DwmEnableMMCSS : 
        enableMMCSS : bool -> HResult 

```


#### Parameters
&nbsp;<dl><dt>enableMMCSS</dt><dd>Type: System.Boolean<br />TRUE to instruct DWM to participate in MMCSS scheduling; FALSE to opt out or end participation in MMCSS scheduling.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmenablemmcss" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmenablemmcss</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />