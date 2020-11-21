# NativeMethods.QueryIdleProcessorCycleTime Method 
 

Retrieves the cycle time for the idle thread of each processor in the system. 

 On a system with more than 64 processors, this function retrieves the cycle time for the idle thread of each processor in the processor group to which the calling thread is assigned. 

 Use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_QueryIdleProcessorCycleTimeEx">QueryIdleProcessorCycleTimeEx(UInt16, UInt32, IntPtr)</a> function to retrieve the cycle time for the idle thread on each logical processor for a specific processor group.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool QueryIdleProcessorCycleTime(
	ref uint refBufferLength,
	IntPtr processorIdleCycleTime
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function QueryIdleProcessorCycleTime ( 
	ByRef refBufferLength As UInteger,
	processorIdleCycleTime As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refBufferLength As UInteger
Dim processorIdleCycleTime As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.QueryIdleProcessorCycleTime(refBufferLength, 
	processorIdleCycleTime)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool QueryIdleProcessorCycleTime(
	unsigned int% refBufferLength, 
	IntPtr processorIdleCycleTime
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member QueryIdleProcessorCycleTime : 
        refBufferLength : uint32 byref * 
        processorIdleCycleTime : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>refBufferLength</dt><dd>Type: System.UInt32<br />On input, specifies the size of the *processorIdleCycleTime* buffer, in bytes. This buffer is expected to be 8 times the number of processors in the group. 

 On output, specifies the number of elements written to the buffer. If the buffer size is not sufficient, the function fails and this parameter receives the required length of the buffer.</dd><dt>processorIdleCycleTime</dt><dd>Type: System.IntPtr<br />The number of CPU clock cycles used by each idle thread. This buffer must be 8 times the number of processors in the system in size.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/realtimeapiset/nf-realtimeapiset-queryidleprocessorcycletime" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/realtimeapiset/nf-realtimeapiset-queryidleprocessorcycletime</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />