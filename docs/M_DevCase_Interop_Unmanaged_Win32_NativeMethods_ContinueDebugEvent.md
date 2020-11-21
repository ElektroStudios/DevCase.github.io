# NativeMethods.ContinueDebugEvent Method 
 

Enables a debugger to continue a thread that previously reported a debugging event.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ContinueDebugEvent(
	uint processId,
	uint threadId,
	ContinueDebugEventFlags continueStatus
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ContinueDebugEvent ( 
	processId As UInteger,
	threadId As UInteger,
	continueStatus As ContinueDebugEventFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim processId As UInteger
Dim threadId As UInteger
Dim continueStatus As ContinueDebugEventFlags
Dim returnValue As Boolean

returnValue = NativeMethods.ContinueDebugEvent(processId, 
	threadId, continueStatus)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool ContinueDebugEvent(
	unsigned int processId, 
	unsigned int threadId, 
	ContinueDebugEventFlags continueStatus
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member ContinueDebugEvent : 
        processId : uint32 * 
        threadId : uint32 * 
        continueStatus : ContinueDebugEventFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>processId</dt><dd>Type: System.UInt32<br />The process identifier of the process to continue</dd><dt>threadId</dt><dd>Type: System.UInt32<br />The thread identifier of the thread to continue. 

 The combination of process identifier and thread identifier must identify a thread that has previously reported a debugging event.</dd><dt>continueStatus</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ContinueDebugEventFlags">DevCase.Interop.Unmanaged.Win32.Enums.ContinueDebugEventFlags</a><br />The options to continue the thread that reported the debugging event</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms679285(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms679285(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />