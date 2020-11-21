# UIAutomationUtil.PauseProcess Method (Int32)
 

Pauses the execution of all the threads of the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static PauseProcessObject PauseProcess(
	int pid
)
```

**VB**<br />
``` VB
Public Shared Function PauseProcess ( 
	pid As Integer
) As PauseProcessObject
```

**VB Usage**<br />
``` VB Usage
Dim pid As Integer
Dim returnValue As PauseProcessObject

returnValue = UIAutomationUtil.PauseProcess(pid)
```

**C++**<br />
``` C++
public:
static PauseProcessObject^ PauseProcess(
	int pid
)
```

**F#**<br />
``` F#
static member PauseProcess : 
        pid : int -> PauseProcessObject 

```


#### Parameters
&nbsp;<dl><dt>pid</dt><dd>Type: System.Int32<br />The process id (PID).</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_IPC_PauseProcessObject">PauseProcessObject</a><br />The return value is a collection of openthread-handles to the thread handles of the process. 

 An openthread-handle could be used to suspend, resume or terminate a thread that the openthread-handle refers to.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## Remarks
After pausing the threads of a process, call <a href="M_DevCase_Core_IPC_Tools_UIAutomationUtil_ResumeProcess">ResumeProcess(PauseProcessObject)</a> function to resume their threads. 

 To manually resume an openthread-handle, call <a href="M_DevCase_Core_IPC_Tools_UIAutomationUtil_ResumeThread">ResumeThread(SafeAccessTokenHandle)</a> function.

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
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_PauseProcess">PauseProcess Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />