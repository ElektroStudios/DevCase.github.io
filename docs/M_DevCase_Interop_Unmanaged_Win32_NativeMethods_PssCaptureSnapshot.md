# NativeMethods.PssCaptureSnapshot Method 
 

Captures a snapshot of a target process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static Win32ErrorCode PssCaptureSnapshot(
	IntPtr processHandle,
	PssCaptureFlags flags,
	uint threadContextFlags,
	out IntPtr refSnapshotHandle
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function PssCaptureSnapshot ( 
	processHandle As IntPtr,
	flags As PssCaptureFlags,
	threadContextFlags As UInteger,
	<OutAttribute> ByRef refSnapshotHandle As IntPtr
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim processHandle As IntPtr
Dim flags As PssCaptureFlags
Dim threadContextFlags As UInteger
Dim refSnapshotHandle As IntPtr
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.PssCaptureSnapshot(processHandle, 
	flags, threadContextFlags, refSnapshotHandle)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static Win32ErrorCode PssCaptureSnapshot(
	IntPtr processHandle, 
	PssCaptureFlags flags, 
	unsigned int threadContextFlags, 
	[OutAttribute] IntPtr% refSnapshotHandle
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member PssCaptureSnapshot : 
        processHandle : IntPtr * 
        flags : PssCaptureFlags * 
        threadContextFlags : uint32 * 
        refSnapshotHandle : IntPtr byref -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>processHandle</dt><dd>Type: System.IntPtr<br />A handle to the target process.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PssCaptureFlags">DevCase.Interop.Unmanaged.Win32.Enums.PssCaptureFlags</a><br />Flags that specify what to capture.</dd><dt>threadContextFlags</dt><dd>Type: System.UInt32<br />The CONTEXT record flags to capture if *flags* parameter specifies thread contexts.</dd><dt>refSnapshotHandle</dt><dd>Type: System.IntPtr<br />A handle to the snapshot that this function captures.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>; othwerise, a different <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/nf-processsnapshot-psscapturesnapshot" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/desktop/api/processsnapshot/nf-processsnapshot-psscapturesnapshot</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />