# NativeMethods.GetProcessVersion Method 
 

Retrieves the major and minor version numbers of the system on which the specified process expects to run.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static uint GetProcessVersion(
	uint processId
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetProcessVersion ( 
	processId As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim processId As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetProcessVersion(processId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static unsigned int GetProcessVersion(
	unsigned int processId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetProcessVersion : 
        processId : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>processId</dt><dd>Type: System.UInt32<br />The process identifier of the process of interest. A value of zero specifies the calling process.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the version of the system on which the process expects to run. The high word of the return value contains the major version number. The low word of the return value contains the minor version number. 

 If the function fails, the return value is zero. 

 The function fails if *processId* is an invalid value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getprocessversion" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getprocessversion</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />