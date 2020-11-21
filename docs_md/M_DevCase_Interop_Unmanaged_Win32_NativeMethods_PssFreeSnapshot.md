# NativeMethods.PssFreeSnapshot Method 
 

Frees a process snapshot. 

 To take a snapshot, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PssCaptureSnapshot">PssCaptureSnapshot(IntPtr, PssCaptureFlags, UInt32, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static Win32ErrorCode PssFreeSnapshot(
	IntPtr processHandle,
	IntPtr snapshotHandle
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function PssFreeSnapshot ( 
	processHandle As IntPtr,
	snapshotHandle As IntPtr
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim processHandle As IntPtr
Dim snapshotHandle As IntPtr
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.PssFreeSnapshot(processHandle, 
	snapshotHandle)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static Win32ErrorCode PssFreeSnapshot(
	IntPtr processHandle, 
	IntPtr snapshotHandle
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member PssFreeSnapshot : 
        processHandle : IntPtr * 
        snapshotHandle : IntPtr -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>processHandle</dt><dd>Type: System.IntPtr<br />A handle to the process that contains the snapshot. 

 The handle must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryRead</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryOperation</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">DuplicateHandle</a> rights. 

 If the snapshot was captured from the current process, or duplicated into the current process, then pass in the result of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetCurrentProcess">GetCurrentProcess()</a>.</dd><dt>snapshotHandle</dt><dd>Type: System.IntPtr<br />A handle to the snapshot to free.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>; othwerise, a different <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processsnapshot/nf-processsnapshot-pssfreesnapshot" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processsnapshot/nf-processsnapshot-pssfreesnapshot</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />