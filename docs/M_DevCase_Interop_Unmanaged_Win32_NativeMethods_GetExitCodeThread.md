# NativeMethods.GetExitCodeThread Method 
 

Retrieves the termination status of the specified thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool GetExitCodeThread(
	IntPtr hThread,
	ref uint refExitCode
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetExitCodeThread ( 
	hThread As IntPtr,
	ByRef refExitCode As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hThread As IntPtr
Dim refExitCode As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.GetExitCodeThread(hThread, 
	refExitCode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool GetExitCodeThread(
	IntPtr hThread, 
	unsigned int% refExitCode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetExitCodeThread : 
        hThread : IntPtr * 
        refExitCode : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hThread</dt><dd>Type: System.IntPtr<br />A handle to the thread. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> access right.</dd><dt>refExitCode</dt><dd>Type: System.UInt32<br />A pointer to a variable to receive the thread termination status.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getexitcodethread" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getexitcodethread</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />