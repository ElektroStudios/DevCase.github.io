# NativeMethods.QueryProcessCycleTime Method 
 

Retrieves the sum of the cycle time of all threads of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool QueryProcessCycleTime(
	IntPtr hProcess,
	out ulong refCycleTime
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function QueryProcessCycleTime ( 
	hProcess As IntPtr,
	<OutAttribute> ByRef refCycleTime As ULong
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim refCycleTime As ULong
Dim returnValue As Boolean

returnValue = NativeMethods.QueryProcessCycleTime(hProcess, 
	refCycleTime)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool QueryProcessCycleTime(
	IntPtr hProcess, 
	[OutAttribute] unsigned long long% refCycleTime
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member QueryProcessCycleTime : 
        hProcess : IntPtr * 
        refCycleTime : uint64 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 The handle must have the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> access right.</dd><dt>refCycleTime</dt><dd>Type: System.UInt64<br />The number of CPU clock cycles used by the threads of the process. This value includes cycles spent in both user mode and kernel mode</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/realtimeapiset/nf-realtimeapiset-queryprocesscycletime" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/realtimeapiset/nf-realtimeapiset-queryprocesscycletime</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />