# UIAutomationUtil.GetScrollbars Method (IWin32Window)
 

Gets a value indicating which are the visible ScrollBars of a Window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ScrollBars GetScrollbars(
	IWin32Window window
)
```

**VB**<br />
``` VB
Public Shared Function GetScrollbars ( 
	window As IWin32Window
) As ScrollBars
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim returnValue As ScrollBars

returnValue = UIAutomationUtil.GetScrollbars(window)
```

**C++**<br />
``` C++
public:
static ScrollBars GetScrollbars(
	IWin32Window^ window
)
```

**F#**<br />
``` F#
static member GetScrollbars : 
        window : IWin32Window -> ScrollBars 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window to retrieve their visible ScrollBars.</dd></dl>

#### Return Value
Type: ScrollBars<br />The visible ScrollBar(s).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim scrollBars As ScrollBars = GetScrollbars(window)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_GetScrollbars">GetScrollbars Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />