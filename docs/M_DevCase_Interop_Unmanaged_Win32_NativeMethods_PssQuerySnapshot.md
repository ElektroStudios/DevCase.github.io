# NativeMethods.PssQuerySnapshot Method 
 

Queries a process snapshot. 

 To take a snapshot, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PssCaptureSnapshot">PssCaptureSnapshot(IntPtr, PssCaptureFlags, UInt32, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static Win32ErrorCode PssQuerySnapshot(
	IntPtr snapshotHandle,
	PssQueryInformationClass informationClass,
	IntPtr buffer,
	uint bufferLength
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function PssQuerySnapshot ( 
	snapshotHandle As IntPtr,
	informationClass As PssQueryInformationClass,
	buffer As IntPtr,
	bufferLength As UInteger
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim snapshotHandle As IntPtr
Dim informationClass As PssQueryInformationClass
Dim buffer As IntPtr
Dim bufferLength As UInteger
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.PssQuerySnapshot(snapshotHandle, 
	informationClass, buffer, bufferLength)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static Win32ErrorCode PssQuerySnapshot(
	IntPtr snapshotHandle, 
	PssQueryInformationClass informationClass, 
	IntPtr buffer, 
	unsigned int bufferLength
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member PssQuerySnapshot : 
        snapshotHandle : IntPtr * 
        informationClass : PssQueryInformationClass * 
        buffer : IntPtr * 
        bufferLength : uint32 -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>snapshotHandle</dt><dd>Type: System.IntPtr<br />A handle to the snapshot to query.</dd><dt>informationClass</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_PssQueryInformationClass">DevCase.Interop.Unmanaged.Win32.Enums.PssQueryInformationClass</a><br />An enumerator member that selects what information to query.</dd><dt>buffer</dt><dd>Type: System.IntPtr<br />The information that this function provides.</dd><dt>bufferLength</dt><dd>Type: System.UInt32<br />The size of *buffer*, in bytes.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>; othwerise, a different <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processsnapshot/nf-processsnapshot-pssquerysnapshot" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processsnapshot/nf-processsnapshot-pssquerysnapshot</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />