# UIAutomationUtil.IsWindowVisible Method (Process)
 

Determines whether the main window of the specified process is visible on the screen (partially obscured by other windows or not).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsWindowVisible(
	Process proc
)
```

**VB**<br />
``` VB
Public Shared Function IsWindowVisible ( 
	proc As Process
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim proc As Process
Dim returnValue As Boolean

returnValue = UIAutomationUtil.IsWindowVisible(proc)
```

**C++**<br />
``` C++
public:
static bool IsWindowVisible(
	Process^ proc
)
```

**F#**<br />
``` F#
static member IsWindowVisible : 
        proc : Process -> bool 

```


#### Parameters
&nbsp;<dl><dt>proc</dt><dd>Type: System.Diagnostics.Process<br />The source process.</dd></dl>

#### Return Value
Type: Boolean<br />\[Missing <returns> documentation for "M:DevCase.Core.IPC.Tools.UIAutomationUtil.IsWindowVisible(System.Diagnostics.Process)"\]

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_IsWindowVisible">IsWindowVisible Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />