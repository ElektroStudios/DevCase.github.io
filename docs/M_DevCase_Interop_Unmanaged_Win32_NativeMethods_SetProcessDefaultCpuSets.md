# NativeMethods.SetProcessDefaultCpuSets Method 
 

Sets the default CPU Sets assignment for threads in the specified process. 

 Threads that are created, which don’t have CPU Sets explicitly set using <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetThreadSelectedCpuSets">SetThreadSelectedCpuSets(IntPtr, UInt32[], UInt32)</a>, will inherit the sets specified by SetProcessDefaultCpuSets(IntPtr, UInt32[], UInt32) automatically.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static bool SetProcessDefaultCpuSets(
	IntPtr hProcess,
	uint[] cpuSetIds,
	uint cpuSetIdCound
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function SetProcessDefaultCpuSets ( 
	hProcess As IntPtr,
	cpuSetIds As UInteger(),
	cpuSetIdCound As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim cpuSetIds As UInteger()
Dim cpuSetIdCound As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.SetProcessDefaultCpuSets(hProcess, 
	cpuSetIds, cpuSetIdCound)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static bool SetProcessDefaultCpuSets(
	[InAttribute] IntPtr hProcess, 
	[InAttribute] array<unsigned int>^ cpuSetIds, 
	unsigned int cpuSetIdCound
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member SetProcessDefaultCpuSets : 
        hProcess : IntPtr * 
        cpuSetIds : uint32[] * 
        cpuSetIdCound : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />Specifies the process for which to set the default CPU Sets. This handle must have the PROCESS_SET_LIMITED_INFORMATION access right. 

 The value returned by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetCurrentProcess">GetCurrentProcess()</a> can also be specified here</dd><dt>cpuSetIds</dt><dd>Type: System.UInt32[]<br />Specifies the list of CPU Set IDs to set as the process default CPU set. 

 If this is NULL, the SetProcessDefaultCpuSets(IntPtr, UInt32[], UInt32) clears out any assignment</dd><dt>cpuSetIdCound</dt><dd>Type: System.UInt32<br />Specifies the number of IDs in the list passed in the *cpuSetIds* argument. 

 If that value is NULL, this should be 0.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/procthread/setprocessdefaultcpusets" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/procthread/setprocessdefaultcpusets</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />