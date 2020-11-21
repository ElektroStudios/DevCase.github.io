# NativeMethods.ProcessIdToSessionId Method 
 

Retrieves the Remote Desktop Services session associated with a specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ProcessIdToSessionId(
	uint processId,
	out uint refSessionId
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ProcessIdToSessionId ( 
	processId As UInteger,
	<OutAttribute> ByRef refSessionId As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim processId As UInteger
Dim refSessionId As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.ProcessIdToSessionId(processId, 
	refSessionId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool ProcessIdToSessionId(
	unsigned int processId, 
	[OutAttribute] unsigned int% refSessionId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member ProcessIdToSessionId : 
        processId : uint32 * 
        refSessionId : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>processId</dt><dd>Type: System.UInt32<br />Specifies a process identifier. 

 Use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetCurrentProcessId">GetCurrentProcessId()</a> function to retrieve the process identifier for the current process.</dd><dt>refSessionId</dt><dd>Type: System.UInt32<br />Pointer to a variable that receives the identifier of the Remote Desktop Services session under which the specified process is running. 

 To retrieve the identifier of the session currently attached to the console, use the WTSGetActiveConsoleSessionId function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-processidtosessionid" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-processidtosessionid</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />