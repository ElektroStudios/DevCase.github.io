# UIAutomationUtil.PauseThread Method (Int32)
 

Pauses the execution of the specified thread.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static SafeAccessTokenHandle PauseThread(
	int threadId
)
```

**VB**<br />
``` VB
Public Shared Function PauseThread ( 
	threadId As Integer
) As SafeAccessTokenHandle
```

**VB Usage**<br />
``` VB Usage
Dim threadId As Integer
Dim returnValue As SafeAccessTokenHandle

returnValue = UIAutomationUtil.PauseThread(threadId)
```

**C++**<br />
``` C++
public:
static SafeAccessTokenHandle^ PauseThread(
	int threadId
)
```

**F#**<br />
``` F#
static member PauseThread : 
        threadId : int -> SafeAccessTokenHandle 

```


#### Parameters
&nbsp;<dl><dt>threadId</dt><dd>Type: System.Int32<br />The thread identifier.</dd></dl>

#### Return Value
Type: SafeAccessTokenHandle<br />The return value is an openthread-handle to the thread handle. 

 An openthread-handle could be used to suspend, resume or terminate a thread that the open-handle refers to.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## Remarks
After pausing a thread, call <a href="M_DevCase_Core_IPC_Tools_UIAutomationUtil_ResumeThread">ResumeThread(SafeAccessTokenHandle)</a> function to resume the thread and close the openthread-handle. 

 To manually close an openthread-handle, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CloseHandle">CloseHandle(IntPtr)</a> function.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim threadId As ProcessThread = Process.GetProcessesByName("cmd.exe").FirstOrDefault.Threads(0).Id

Dim openThreadHandle As SafeAccessTokenHandle = PauseThread(threadId)

' ResumeThread(openThreadHandle)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_PauseThread">PauseThread Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />