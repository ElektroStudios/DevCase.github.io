# ThreadErrorMode Enumeration
 

Specifies a thread error mode. 

 Enumeration used by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetThreadErrorMode">SetThreadErrorMode(ThreadErrorMode, ThreadErrorMode)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ThreadErrorMode
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ThreadErrorMode
```

**VB Usage**<br />
``` VB Usage
Dim instance As ThreadErrorMode
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ThreadErrorMode
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ThreadErrorMode
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadErrorMode.SystemDefault">**SystemDefault**</td><td>0</td><td>Use the system default, which is to display all error dialog boxes.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadErrorMode.FailCriticalErrors">**FailCriticalErrors**</td><td>1</td><td>The system does not display the critical-error-handler message box. Instead, the system sends the error to the current thread. 

 Best practice is that all applications call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetErrorMode">SetErrorMode(ProcessErrorMode)</a> function with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessErrorMode">FailCriticalErrors</a> at startup. This is to prevent error mode dialogs from hanging the application.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadErrorMode.NoGPUFaultErrorBox">**NoGPUFaultErrorBox**</td><td>2</td><td>The system does not display the Windows Error Reporting dialog.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThreadErrorMode.NoOpenFileErrorBox">**NoOpenFileErrorBox**</td><td>32768</td><td>The system does not display a message box when it fails to find a file. Instead, the error is returned to the current thread.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd553630%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd553630%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />