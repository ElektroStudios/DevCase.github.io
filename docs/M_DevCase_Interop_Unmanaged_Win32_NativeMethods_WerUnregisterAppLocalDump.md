# NativeMethods.WerUnregisterAppLocalDump Method 
 

Cancels the registration that was made by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WerRegisterAppLocalDump">WerRegisterAppLocalDump(String)</a> function to specify that Windows Error Reporting (WER) should save a copy of the diagnostic memory dump that WER collects when one of the processes for the application stops responding.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", ExactSpelling = true)]
public static HResult WerUnregisterAppLocalDump()
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", ExactSpelling := true>]
Public Shared Function WerUnregisterAppLocalDump As HResult
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As HResult

returnValue = NativeMethods.WerUnregisterAppLocalDump()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", ExactSpelling = true)]
static HResult WerUnregisterAppLocalDump()
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", ExactSpelling = true)>]
static member WerUnregisterAppLocalDump : unit -> HResult 

```


#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werunregisterapplocaldump" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werunregisterapplocaldump</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />