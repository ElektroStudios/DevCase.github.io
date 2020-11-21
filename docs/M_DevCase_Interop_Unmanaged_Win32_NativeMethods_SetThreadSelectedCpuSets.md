# NativeMethods.SetThreadSelectedCpuSets Method 
 

Sets the selected CPU Sets assignment for the specified thread. This assignment overrides the process default assignment, if one is set.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static bool SetThreadSelectedCpuSets(
	IntPtr hThread,
	uint[] cpuSetIds,
	uint cpuSetIdCount
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function SetThreadSelectedCpuSets ( 
	hThread As IntPtr,
	cpuSetIds As UInteger(),
	cpuSetIdCount As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hThread As IntPtr
Dim cpuSetIds As UInteger()
Dim cpuSetIdCount As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.SetThreadSelectedCpuSets(hThread, 
	cpuSetIds, cpuSetIdCount)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static bool SetThreadSelectedCpuSets(
	[InAttribute] IntPtr hThread, 
	array<unsigned int>^ cpuSetIds, 
	unsigned int cpuSetIdCount
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member SetThreadSelectedCpuSets : 
        hThread : IntPtr * 
        cpuSetIds : uint32[] * 
        cpuSetIdCount : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>hThread</dt><dd>Type: System.IntPtr<br />Specifies the thread on which to set the CPU Set assignment. 

 This handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">SetLimitedInformation</a> access right. 

 The value returned by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetCurrentThread">GetCurrentThread()</a> can also be used.</dd><dt>cpuSetIds</dt><dd>Type: System.UInt32[]<br />Specifies the list of CPU Set IDs to set as the thread selected CPU set. 

 If this parameter is NULL, the function clears out any assignment, reverting to process default assignment if one is set.</dd><dt>cpuSetIdCount</dt><dd>Type: System.UInt32<br />Specifies the number of IDs in the list passed in the *cpuSetIds* argument. 

 If that value is NULL, this should be 0.</dd></dl>

#### Return Value
Type: Boolean<br />This function cannot fail when passed valid parameters.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/procthread/setthreadselectedcpusets" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/procthread/setthreadselectedcpusets</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />