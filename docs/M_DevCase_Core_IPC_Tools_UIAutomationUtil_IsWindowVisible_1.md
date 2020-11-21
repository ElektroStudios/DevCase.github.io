# UIAutomationUtil.IsWindowVisible Method (IntPtr)
 

Determines whether the specified window is visible on the screen (partially obscured by other windows or not).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsWindowVisible(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
Public Shared Function IsWindowVisible ( 
	hWnd As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim returnValue As Boolean

returnValue = UIAutomationUtil.IsWindowVisible(hWnd)
```

**C++**<br />
``` C++
public:
static bool IsWindowVisible(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
static member IsWindowVisible : 
        hWnd : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the window.</dd></dl>

#### Return Value
Type: Boolean<br />\[Missing <returns> documentation for "M:DevCase.Core.IPC.Tools.UIAutomationUtil.IsWindowVisible(System.IntPtr)"\]

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_IsWindowVisible">IsWindowVisible Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />