# NativeMethods.GetSystemTimes Method 
 

Retrieves system timing information. On a multiprocessor system, the values returned are the sum of the designated times across all processors.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool GetSystemTimes(
	out FILETIME refIdleTime,
	out FILETIME refKernelTime,
	out FILETIME refUserTime
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetSystemTimes ( 
	<OutAttribute> ByRef refIdleTime As FILETIME,
	<OutAttribute> ByRef refKernelTime As FILETIME,
	<OutAttribute> ByRef refUserTime As FILETIME
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refIdleTime As FILETIME
Dim refKernelTime As FILETIME
Dim refUserTime As FILETIME
Dim returnValue As Boolean

returnValue = NativeMethods.GetSystemTimes(refIdleTime, 
	refKernelTime, refUserTime)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool GetSystemTimes(
	[OutAttribute] FILETIME% refIdleTime, 
	[OutAttribute] FILETIME% refKernelTime, 
	[OutAttribute] FILETIME% refUserTime
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetSystemTimes : 
        refIdleTime : FILETIME byref * 
        refKernelTime : FILETIME byref * 
        refUserTime : FILETIME byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refIdleTime</dt><dd>Type: System.Runtime.InteropServices.ComTypes.FILETIME<br />A pointer to a FILETIME structure that receives the amount of time that the system has been idle.</dd><dt>refKernelTime</dt><dd>Type: System.Runtime.InteropServices.ComTypes.FILETIME<br />A pointer to a FILETIME structure that receives the amount of time that the system has spent executing in Kernel mode (including all threads in all processes, on all processors). 

 This time value also includes the amount of time the system has been idle.</dd><dt>refUserTime</dt><dd>Type: System.Runtime.InteropServices.ComTypes.FILETIME<br />A pointer to a FILETIME structure that receives the amount of time that the system has spent executing in User mode (including all threads in all processes, on all processors).</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getsystemtimes" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-getsystemtimes</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />