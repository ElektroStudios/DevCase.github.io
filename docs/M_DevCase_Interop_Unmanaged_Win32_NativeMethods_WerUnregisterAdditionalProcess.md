# NativeMethods.WerUnregisterAdditionalProcess Method 
 

Removes a process from the list of additional processes to be included in the error report.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static HResult WerUnregisterAdditionalProcess(
	uint processId
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function WerUnregisterAdditionalProcess ( 
	processId As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim processId As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.WerUnregisterAdditionalProcess(processId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static HResult WerUnregisterAdditionalProcess(
	unsigned int processId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member WerUnregisterAdditionalProcess : 
        processId : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>processId</dt><dd>Type: System.UInt32<br />The Id of the process to remove. 

 It must have been previously registered with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WerRegisterAdditionalProcess">WerRegisterAdditionalProcess(UInt32, UInt32)</a>.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werunregisteradditionalprocess" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werunregisteradditionalprocess</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />