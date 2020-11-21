# NativeMethods.NtSuspendProcess Method 
 

Suspends a process. 

 When you suspend a process, all the threads of the process will be set to a suspended state. 

 This cuts off code execution until we resume the process, which consists of resuming each thread under the process which was put into a suspended state.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", SetLastError = true)]
public static NTStatus NtSuspendProcess(
	IntPtr processHandle
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", SetLastError := true>]
Public Shared Function NtSuspendProcess ( 
	processHandle As IntPtr
) As NTStatus
```

**VB Usage**<br />
``` VB Usage
Dim processHandle As IntPtr
Dim returnValue As NTStatus

returnValue = NativeMethods.NtSuspendProcess(processHandle)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", SetLastError = true)]
static NTStatus NtSuspendProcess(
	IntPtr processHandle
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", SetLastError = true)>]
static member NtSuspendProcess : 
        processHandle : IntPtr -> NTStatus 

```


#### Parameters
&nbsp;<dl><dt>processHandle</dt><dd>Type: System.IntPtr<br />A handle to the process to suspend.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">SUCCESS</a> on success.

## Remarks
<a href="https://ntopcode.wordpress.com/tag/ntsuspendprocess/" target="_blank">https://ntopcode.wordpress.com/tag/ntsuspendprocess/</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />