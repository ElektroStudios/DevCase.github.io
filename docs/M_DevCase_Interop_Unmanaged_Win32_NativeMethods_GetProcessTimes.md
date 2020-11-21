# NativeMethods.GetProcessTimes Method 
 

Retrieves timing information for the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool GetProcessTimes(
	IntPtr hProcess,
	out FILETIME refCreationTime,
	out FILETIME refExitTime,
	out FILETIME refKernelTime,
	out FILETIME refUserTime
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetProcessTimes ( 
	hProcess As IntPtr,
	<OutAttribute> ByRef refCreationTime As FILETIME,
	<OutAttribute> ByRef refExitTime As FILETIME,
	<OutAttribute> ByRef refKernelTime As FILETIME,
	<OutAttribute> ByRef refUserTime As FILETIME
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim refCreationTime As FILETIME
Dim refExitTime As FILETIME
Dim refKernelTime As FILETIME
Dim refUserTime As FILETIME
Dim returnValue As Boolean

returnValue = NativeMethods.GetProcessTimes(hProcess, 
	refCreationTime, refExitTime, refKernelTime, 
	refUserTime)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool GetProcessTimes(
	[InAttribute] IntPtr hProcess, 
	[OutAttribute] FILETIME% refCreationTime, 
	[OutAttribute] FILETIME% refExitTime, 
	[OutAttribute] FILETIME% refKernelTime, 
	[OutAttribute] FILETIME% refUserTime
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetProcessTimes : 
        hProcess : IntPtr * 
        refCreationTime : FILETIME byref * 
        refExitTime : FILETIME byref * 
        refKernelTime : FILETIME byref * 
        refUserTime : FILETIME byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process whose timing information is sought. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> access right.</dd><dt>refCreationTime</dt><dd>Type: System.Runtime.InteropServices.ComTypes.FILETIME<br />A pointer to a FILETIME structure that receives the creation time of the process.</dd><dt>refExitTime</dt><dd>Type: System.Runtime.InteropServices.ComTypes.FILETIME<br />A pointer to a FILETIME structure that receives the exit time of the process. 

 If the process has not exited, the content of this structure is undefined.</dd><dt>refKernelTime</dt><dd>Type: System.Runtime.InteropServices.ComTypes.FILETIME<br />A pointer to a FILETIME structure that receives the amount of time that the process has executed in kernel mode. 

 The time that each of the threads of the process has executed in kernel mode is determined, and then all of those times are summed together to obtain this value.</dd><dt>refUserTime</dt><dd>Type: System.Runtime.InteropServices.ComTypes.FILETIME<br />A pointer to a FILETIME structure that receives the amount of time that the process has executed in user mode. 

 The time that each of the threads of the process has executed in user mode is determined, and then all of those times are summed together to obtain this value. 

 Note that this value can exceed the amount of real time elapsed (between *refCreationTime* and *refExitTime*) if the process executes across multiple CPU cores.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getprocesstimes" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getprocesstimes</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />