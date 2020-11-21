# NativeMethods.WerRegisterAdditionalProcess Method 
 

Registers a process to be included in the error report along with the main application process. 

 Optionally specifies a thread within that registered process to get additional data from.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static HResult WerRegisterAdditionalProcess(
	uint processId,
	uint captureExtraInfoForThreadId
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function WerRegisterAdditionalProcess ( 
	processId As UInteger,
	captureExtraInfoForThreadId As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim processId As UInteger
Dim captureExtraInfoForThreadId As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.WerRegisterAdditionalProcess(processId, 
	captureExtraInfoForThreadId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static HResult WerRegisterAdditionalProcess(
	unsigned int processId, 
	unsigned int captureExtraInfoForThreadId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member WerRegisterAdditionalProcess : 
        processId : uint32 * 
        captureExtraInfoForThreadId : uint32 -> HResult 

```


#### Parameters
&nbsp;<dl><dt>processId</dt><dd>Type: System.UInt32<br />The Id of the process to register.</dd><dt>captureExtraInfoForThreadId</dt><dd>Type: System.UInt32<br />The Id of a thread within the registered process from which more information is requested.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code on failure.

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregisteradditionalprocess" target="_blank">https://docs.microsoft.com/es-es/windows/desktop/api/werapi/nf-werapi-werregisteradditionalprocess</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />