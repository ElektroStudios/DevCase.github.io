# NativeMethods.PssDuplicateSnapshot Method 
 

Duplicates a snapshot handle from one process to another. 

 To take a snapshot, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PssCaptureSnapshot">PssCaptureSnapshot(IntPtr, PssCaptureFlags, UInt32, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static Win32ErrorCode PssDuplicateSnapshot(
	IntPtr sourceProcessHandle,
	IntPtr snapshotHandle,
	IntPtr targetProcessHandle,
	out IntPtr refTargetSnapshotHandle,
	PssDuplicateFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function PssDuplicateSnapshot ( 
	sourceProcessHandle As IntPtr,
	snapshotHandle As IntPtr,
	targetProcessHandle As IntPtr,
	<OutAttribute> ByRef refTargetSnapshotHandle As IntPtr,
	flags As PssDuplicateFlags
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim sourceProcessHandle As IntPtr
Dim snapshotHandle As IntPtr
Dim targetProcessHandle As IntPtr
Dim refTargetSnapshotHandle As IntPtr
Dim flags As PssDuplicateFlags
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.PssDuplicateSnapshot(sourceProcessHandle, 
	snapshotHandle, targetProcessHandle, 
	refTargetSnapshotHandle, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static Win32ErrorCode PssDuplicateSnapshot(
	IntPtr sourceProcessHandle, 
	IntPtr snapshotHandle, 
	IntPtr targetProcessHandle, 
	[OutAttribute] IntPtr% refTargetSnapshotHandle, 
	PssDuplicateFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member PssDuplicateSnapshot : 
        sourceProcessHandle : IntPtr * 
        snapshotHandle : IntPtr * 
        targetProcessHandle : IntPtr * 
        refTargetSnapshotHandle : IntPtr byref * 
        flags : PssDuplicateFlags -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>sourceProcessHandle</dt><dd>Type: System.IntPtr<br />A handle to the source process from which the original snapshot was captured. 

 The handle must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryRead</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">DuplicateHandle</a> rights.</dd><dt>snapshotHandle</dt><dd>Type: System.IntPtr<br />A handle to the snapshot to duplicate. This handle must be in the context of the source process.</dd><dt>targetProcessHandle</dt><dd>Type: System.IntPtr<br />A handle to the target process that receives the duplicate snapshot. 

 The handle must have <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryOperation</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">VirtualMemoryWrite</a>, and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">DuplicateHandle</a> rights.</dd><dt>refTargetSnapshotHandle</dt><dd>Type: System.IntPtr<br />A handle to the duplicate snapshot that this function creates, in the context of the target process.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PssDuplicateFlags">DevCase.Interop.Unmanaged.Win32.Enums.PssDuplicateFlags</a><br />The duplication flags.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>; othwerise, a different <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/nf-processsnapshot-pssduplicatesnapshot" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/nf-processsnapshot-pssduplicatesnapshot</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />