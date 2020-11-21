# NativeMethods.SetThreadPriority Method 
 

Sets the priority value for the specified thread. 

 This value, together with the priority class of the thread's process, determines the thread's base priority level.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static bool SetThreadPriority(
	IntPtr hThread,
	ThreadPriorityLevel nPriority
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function SetThreadPriority ( 
	hThread As IntPtr,
	nPriority As ThreadPriorityLevel
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hThread As IntPtr
Dim nPriority As ThreadPriorityLevel
Dim returnValue As Boolean

returnValue = NativeMethods.SetThreadPriority(hThread, 
	nPriority)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static bool SetThreadPriority(
	IntPtr hThread, 
	ThreadPriorityLevel nPriority
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member SetThreadPriority : 
        hThread : IntPtr * 
        nPriority : ThreadPriorityLevel -> bool 

```


#### Parameters
&nbsp;<dl><dt>hThread</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 This handle must be created with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">SetInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadAccessRights">SetLimitedInformation</a> access right.</dd><dt>nPriority</dt><dd>Type: System.Diagnostics.ThreadPriorityLevel<br />The priority value for the thread.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms686277%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms686277%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />