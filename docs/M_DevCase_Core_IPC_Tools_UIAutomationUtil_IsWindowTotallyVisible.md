# UIAutomationUtil.IsWindowTotallyVisible Method (Process)
 

Determines whether the main window of the specified process is totally visible on the screen; this means the window is not obscured by other windows and is not off screen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsWindowTotallyVisible(
	Process proc
)
```

**VB**<br />
``` VB
Public Shared Function IsWindowTotallyVisible ( 
	proc As Process
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim proc As Process
Dim returnValue As Boolean

returnValue = UIAutomationUtil.IsWindowTotallyVisible(proc)
```

**C++**<br />
``` C++
public:
static bool IsWindowTotallyVisible(
	Process^ proc
)
```

**F#**<br />
``` F#
static member IsWindowTotallyVisible : 
        proc : Process -> bool 

```


#### Parameters
&nbsp;<dl><dt>proc</dt><dd>Type: System.Diagnostics.Process<br />The source process.</dd></dl>

#### Return Value
Type: Boolean<br />\[Missing <returns> documentation for "M:DevCase.Core.IPC.Tools.UIAutomationUtil.IsWindowTotallyVisible(System.Diagnostics.Process)"\]

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_IsWindowTotallyVisible">IsWindowTotallyVisible Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />