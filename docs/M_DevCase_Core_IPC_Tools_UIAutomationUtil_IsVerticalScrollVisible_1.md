# UIAutomationUtil.IsVerticalScrollVisible Method (IWin32Window)
 

Determines whether a Vertical Scrollbar its shown in a window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsVerticalScrollVisible(
	IWin32Window window
)
```

**VB**<br />
``` VB
Public Shared Function IsVerticalScrollVisible ( 
	window As IWin32Window
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim returnValue As Boolean

returnValue = UIAutomationUtil.IsVerticalScrollVisible(window)
```

**C++**<br />
``` C++
public:
static bool IsVerticalScrollVisible(
	IWin32Window^ window
)
```

**F#**<br />
``` F#
static member IsVerticalScrollVisible : 
        window : IWin32Window -> bool 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if vertical scrollbar its shown; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isVScrollBarVisible As Boolean = IsVerticalScrollVisible(window)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_IsVerticalScrollVisible">IsVerticalScrollVisible Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />