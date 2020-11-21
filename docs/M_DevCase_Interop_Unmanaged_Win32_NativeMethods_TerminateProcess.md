# NativeMethods.TerminateProcess Method 
 

Terminates the specified process and all of its threads.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool TerminateProcess(
	IntPtr hProcess,
	uint exitCode
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function TerminateProcess ( 
	hProcess As IntPtr,
	exitCode As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim exitCode As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.TerminateProcess(hProcess, 
	exitCode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool TerminateProcess(
	[InAttribute] IntPtr hProcess, 
	unsigned int exitCode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member TerminateProcess : 
        hProcess : IntPtr * 
        exitCode : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process to be terminated. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">Terminate</a> access right.</dd><dt>exitCode</dt><dd>Type: System.UInt32<br />The exit code to be used by the process and threads terminated as a result of this call. 

 Use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetExitCodeProcess">GetExitCodeProcess(IntPtr, UInt32)</a> function to retrieve a process's exit value. 

 Use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetExitCodeThread">GetExitCodeThread(IntPtr, UInt32)</a> function to retrieve a thread's exit value.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-terminateprocess" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-terminateprocess</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />