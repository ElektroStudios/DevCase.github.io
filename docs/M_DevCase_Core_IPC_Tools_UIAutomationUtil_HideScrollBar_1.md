# UIAutomationUtil.HideScrollBar Method (IWin32Window, ScrollBars)
 

Hides the specified scrollbar of a window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool HideScrollBar(
	IWin32Window window,
	ScrollBars scrollBars
)
```

**VB**<br />
``` VB
Public Shared Function HideScrollBar ( 
	window As IWin32Window,
	scrollBars As ScrollBars
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim scrollBars As ScrollBars
Dim returnValue As Boolean

returnValue = UIAutomationUtil.HideScrollBar(window, 
	scrollBars)
```

**C++**<br />
``` C++
public:
static bool HideScrollBar(
	IWin32Window^ window, 
	ScrollBars scrollBars
)
```

**F#**<br />
``` F#
static member HideScrollBar : 
        window : IWin32Window * 
        scrollBars : ScrollBars -> bool 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window.</dd><dt>scrollBars</dt><dd>Type: System.Windows.Forms.ScrollBars<br />The scrollbar(s) to be shown.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) If the function succeeds, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
HideScrollBar(window, ScrollBars.Horizontal)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_HideScrollBar">HideScrollBar Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />