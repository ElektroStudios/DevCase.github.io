# WaitObjectResult Enumeration
 

Specifies the event that caused the functions <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WaitForSingleObject">WaitForSingleObject(IntPtr, UInt32)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WaitForSingleObjectEx">WaitForSingleObjectEx(IntPtr, UInt32, Boolean)</a> to return.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum WaitObjectResult
```

**VB**<br />
``` VB
Public Enumeration WaitObjectResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As WaitObjectResult
```

**C++**<br />
``` C++
public enum class WaitObjectResult
```

**F#**<br />
``` F#
type WaitObjectResult
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WaitObjectResult.Abandoned">**Abandoned**</td><td>128</td><td>The specified object is a mutex object that was not released by the thread that owned the mutex object before the owning thread terminated. 

 Ownership of the mutex object is granted to the calling thread and the mutex state is set to nonsignaled. 

 the mutex was protecting persistent state information, you should check it for consistency.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WaitObjectResult.IOCompletion">**IOCompletion**</td><td>192</td><td>The wait was ended by one or more user-mode asynchronous procedure calls (APC) queued to the thread.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WaitObjectResult.Object0">**Object0**</td><td>0</td><td>The state of the specified object is signaled.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WaitObjectResult.Timeout">**Timeout**</td><td>258</td><td>The time-out interval elapsed, and the object's state is nonsignaled.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WaitObjectResult.Failed">**Failed**</td><td>4294967295</td><td>The function has failed. To get extended error information, call GetLastWin32Error().</td></tr></table>

## Remarks
WaitForSingleObject function: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms687032(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms687032(v=vs.85).aspx</a>

 WaitForSingleObjectEx function: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms687036(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms687036(v=vs.85).aspx</a>

 WaitForMultipleObjects function: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms687025(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms687025(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />