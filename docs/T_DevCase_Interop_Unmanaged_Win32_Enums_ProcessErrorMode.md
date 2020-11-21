# ProcessErrorMode Enumeration
 

Specifies the error mode for a process. 

 Flags used by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetErrorMode">GetErrorMode()</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetErrorMode">SetErrorMode(ProcessErrorMode)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ProcessErrorMode
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ProcessErrorMode
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessErrorMode
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ProcessErrorMode
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ProcessErrorMode
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessErrorMode.Default">**Default**</td><td>0</td><td>Use the system default, which is to display all error dialog boxes.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessErrorMode.FailCriticalErrors">**FailCriticalErrors**</td><td>1</td><td>The system does not display the critical-error-handler message box. Instead, the system sends the error to the current process. 

 Best practice is that all applications call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetErrorMode">SetErrorMode(ProcessErrorMode)</a> function with FailCriticalErrors at startup. This is to prevent error mode dialogs from hanging the application.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessErrorMode.NoAlignmentFaultException">**NoAlignmentFaultException**</td><td>4</td><td>The system automatically fixes memory alignment faults and makes them invisible to the application. 

 It does this for the current process and any descendant processes. 

 This feature is only supported by certain processor architectures. 

 After this value is set for a process, subsequent attempts to clear the value are ignored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessErrorMode.NoGpFaultErrorBox">**NoGpFaultErrorBox**</td><td>2</td><td>The system does not display the Windows Error Reporting dialog.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ProcessErrorMode.NoOpenFileErrorBox">**NoOpenFileErrorBox**</td><td>32768</td><td>The system does not display a message box when it fails to find a file. Instead, the error is returned to the current process.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms679355(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms679355(v=vs.85).aspx</a><a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680621(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680621(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />