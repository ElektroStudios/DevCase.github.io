# UIAutomationUtil.ResumeThread Method (IntPtr)
 

Resumes the execution of the specified thread.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ResumeThread(
	IntPtr openThreadHandle
)
```

**VB**<br />
``` VB
Public Shared Sub ResumeThread ( 
	openThreadHandle As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim openThreadHandle As IntPtrUIAutomationUtil.ResumeThread(openThreadHandle)
```

**C++**<br />
``` C++
public:
static void ResumeThread(
	IntPtr openThreadHandle
)
```

**F#**<br />
``` F#
static member ResumeThread : 
        openThreadHandle : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>openThreadHandle</dt><dd>Type: System.IntPtr<br />An open thread handle. 

 This handle can be obtained by calling the <a href="M_DevCase_Core_IPC_Tools_UIAutomationUtil_PauseThread">PauseThread(ProcessThread)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenThread_1">OpenThread(ThreadAccessRights, Boolean, UInt32)</a> functions.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_ResumeThread">ResumeThread Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />