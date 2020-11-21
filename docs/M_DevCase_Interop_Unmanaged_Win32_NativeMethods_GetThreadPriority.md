# NativeMethods.GetThreadPriority Method 
 

Retrieves the priority class for the specified process. 

 This value, together with the priority value of each thread of the process, determines each thread's base priority level.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static ThreadPriorityLevel GetThreadPriority(
	IntPtr hThread
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function GetThreadPriority ( 
	hThread As IntPtr
) As ThreadPriorityLevel
```

**VB Usage**<br />
``` VB Usage
Dim hThread As IntPtr
Dim returnValue As ThreadPriorityLevel

returnValue = NativeMethods.GetThreadPriority(hThread)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static ThreadPriorityLevel GetThreadPriority(
	IntPtr hThread
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetThreadPriority : 
        hThread : IntPtr -> ThreadPriorityLevel 

```


#### Parameters
&nbsp;<dl><dt>hThread</dt><dd>Type: System.IntPtr<br />A handle to the thread. 

 This handle must be created with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">QueryLimitedInformation</a> access right.</dd></dl>

#### Return Value
Type: ThreadPriorityLevel<br />If the function succeeds, the return value is the thread's priority level. 

 If the function fails, the return value is `THREAD_PRIORITY_ERROR_RETURN` (`0x7FFFFFFFFFFFFFFF`). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms683235%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms683235%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />