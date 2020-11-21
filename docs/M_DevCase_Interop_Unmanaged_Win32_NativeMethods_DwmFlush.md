# NativeMethods.DwmFlush Method 
 

Issues a flush call that blocks the caller until the next present, when all of the Microsoft DirectX surface updates that are currently outstanding have been made. 

 This compensates for very complex scenes or calling processes with very low priority.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll", ExactSpelling = true)]
public static HResult DwmFlush()
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll", ExactSpelling := true>]
Public Shared Function DwmFlush As HResult
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As HResult

returnValue = NativeMethods.DwmFlush()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll", ExactSpelling = true)]
static HResult DwmFlush()
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll", ExactSpelling = true)>]
static member DwmFlush : unit -> HResult 

```


#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmflush" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/nf-dwmapi-dwmflush</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />