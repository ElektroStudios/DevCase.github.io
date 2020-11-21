# NativeMethods.ExitProcess Method 
 

Ends the calling process and all its threads.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static void ExitProcess(
	uint exitCode
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Sub ExitProcess ( 
	exitCode As UInteger
)
```

**VB Usage**<br />
``` VB Usage
Dim exitCode As UInteger

NativeMethods.ExitProcess(exitCode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static void ExitProcess(
	unsigned int exitCode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member ExitProcess : 
        exitCode : uint32 -> unit 

```


#### Parameters
&nbsp;<dl><dt>exitCode</dt><dd>Type: System.UInt32<br />The exit code for the process and all threads.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-exitprocess" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-exitprocess</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />