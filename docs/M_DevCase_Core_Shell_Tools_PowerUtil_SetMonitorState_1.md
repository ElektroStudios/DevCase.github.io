# PowerUtil.SetMonitorState Method (IntPtr, MonitorState)
 

Sets the state of the monitor.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetMonitorState(
	IntPtr hWnd,
	MonitorState state
)
```

**VB**<br />
``` VB
Public Shared Sub SetMonitorState ( 
	hWnd As IntPtr,
	state As MonitorState
)
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim state As MonitorStatePowerUtil.SetMonitorState(hWnd, state)
```

**C++**<br />
``` C++
public:
static void SetMonitorState(
	IntPtr hWnd, 
	MonitorState state
)
```

**F#**<br />
``` F#
static member SetMonitorState : 
        hWnd : IntPtr * 
        state : MonitorState -> unit 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />An IntPtr handle to the window who sill request the monitor state.</dd><dt>state</dt><dd>Type: <a href="T_DevCase_Core_Shell_MonitorState">DevCase.Core.Shell.MonitorState</a><br />The target state of the monitor.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_PowerUtil">PowerUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_PowerUtil_SetMonitorState">SetMonitorState Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />