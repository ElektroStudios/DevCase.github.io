# NativeMethods.NtResumeProcess Method 
 

Resumes a suspended process. 

 To suspend a process, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtSuspendProcess">NtSuspendProcess(IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", SetLastError = true)]
public static NTStatus NtResumeProcess(
	IntPtr processHandle
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", SetLastError := true>]
Public Shared Function NtResumeProcess ( 
	processHandle As IntPtr
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim processHandle As IntPtr
Dim returnValue As NTStatus

returnValue = NativeMethods.NtResumeProcess(processHandle)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", SetLastError = true)]
static NTStatus NtResumeProcess(
	IntPtr processHandle
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", SetLastError = true)>]
static member NtResumeProcess : 
        processHandle : IntPtr -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>processHandle</dt><dd>Type: System.IntPtr<br />A handle to the process to resume.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success.

## Remarks
<a href="https://ntopcode.wordpress.com/tag/ntsuspendprocess/" target="_blank">https://ntopcode.wordpress.com/tag/ntsuspendprocess/</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />