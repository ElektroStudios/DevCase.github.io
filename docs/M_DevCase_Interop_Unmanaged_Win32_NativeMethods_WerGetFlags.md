# NativeMethods.WerGetFlags Method 
 

Retrieves the fault reporting settings for the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static HResult WerGetFlags(
	IntPtr hProcess,
	out WerFaultReporting refFlags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function WerGetFlags ( 
	hProcess As IntPtr,
	<OutAttribute> ByRef refFlags As WerFaultReporting
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim refFlags As WerFaultReporting
Dim returnValue As HResult

returnValue = NativeMethods.WerGetFlags(hProcess, 
	refFlags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static HResult WerGetFlags(
	IntPtr hProcess, 
	[OutAttribute] WerFaultReporting% refFlags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member WerGetFlags : 
        hProcess : IntPtr * 
        refFlags : WerFaultReporting byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 This handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryRead</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> access right.</dd><dt>refFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WerFaultReporting">DevCase.Interop.Unmanaged.Win32.Enums.WerFaultReporting</a><br />Flags.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-wergetflags" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-wergetflags</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />