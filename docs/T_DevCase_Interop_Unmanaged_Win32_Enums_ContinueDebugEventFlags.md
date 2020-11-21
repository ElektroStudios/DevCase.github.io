# ContinueDebugEventFlags Enumeration
 

The options to continue the thread that reported the debugging event for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ContinueDebugEvent">ContinueDebugEvent(UInt32, UInt32, ContinueDebugEventFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ContinueDebugEventFlags
```

**VB**<br />
``` VB
Public Enumeration ContinueDebugEventFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ContinueDebugEventFlags
```

**C++**<br />
``` C++
public enum class ContinueDebugEventFlags
```

**F#**<br />
``` F#
type ContinueDebugEventFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ContinueDebugEventFlags.Continue">**Continue**</td><td>65538</td><td>If the thread specified by the threadId parameter previously reported an EXCEPTION_DEBUG_EVENT debugging event, the function stops all exception processing and continues the thread and the exception is marked as handled. 

 For any other debugging event, this flag simply continues the thread.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ContinueDebugEventFlags.ExceptionNotHandled">**ExceptionNotHandled**</td><td>2147549185</td><td>If the thread specified by threadId parameter previously reported an EXCEPTION_DEBUG_EVENT debugging event, the function continues exception processing. 

 If this is a first-chance exception event, the search and dispatch logic of the structured exception handler is used; otherwise, the process is terminated. 

 For any other debugging event, this flag simply continues the thread.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ContinueDebugEventFlags.ReplyLater">**ReplyLater**</td><td>1073807361</td><td>Supported in Windows 10, version 1507 or above. 

 This flag causes threadId parameter to replay the existing breaking event after the target continues. 

 By calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SuspendThread32">SuspendThread32(SafeAccessTokenHandle)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SuspendThread64">SuspendThread64(SafeAccessTokenHandle)</a> function against threadId parameter, a debugger can resume other threads in the process and later return to the breaking.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms679285(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms679285(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />