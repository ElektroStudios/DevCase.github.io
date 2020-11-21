# UIAutomationUtil.ResumeProcess Method 
 

Resumes the execution of all the threads for the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ResumeProcess(
	PauseProcessObject ppo
)
```

**VB**<br />
``` VB
Public Shared Sub ResumeProcess ( 
	ppo As PauseProcessObject
)
```

**VB Usage**<br />
``` VB Usage
Dim ppo As PauseProcessObjectUIAutomationUtil.ResumeProcess(ppo)
```

**C++**<br />
``` C++
public:
static void ResumeProcess(
	PauseProcessObject^ ppo
)
```

**F#**<br />
``` F#
static member ResumeProcess : 
        ppo : PauseProcessObject -> unit 

```


#### Parameters
&nbsp;<dl><dt>ppo</dt><dd>Type: <a href="T_DevCase_Core_IPC_PauseProcessObject">DevCase.Core.IPC.PauseProcessObject</a><br />A <a href="T_DevCase_Core_IPC_PauseProcessObject">PauseProcessObject</a> object containing all the process thread-handles.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## Remarks
After resuming the threads of a process, call the <a href="M_DevCase_Core_IPC_PauseProcessObject_Dispose">Dispose()</a> method of the *ppo* parameter to close their openthread-handles. 

 To manually close an openthread-handle, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CloseHandle">CloseHandle(IntPtr)</a> function.

## Examples
This is a code example. 
**VB**<br />
``` VB
' Create and run a CMD process.
Dim p As New Process
p.StartInfo.FileName = "cmd.exe"
p.StartInfo.Arguments = "/C ""Dir /B /S /A C:\*"""
p.Start()

Thread.Sleep(2000) ' Let the CMD run the job for some seconds...

' Pause the process.
Using ppo As PauseProcessObject = UIAutomationUtil.PauseProcess(p.Id)
    ' Wait 5 seconds to let you observe that the process is paused...
    Thread.Sleep(5000)

    ' Resume the process.
    UIAutomationUtil.ResumeProcess(ppo)
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />