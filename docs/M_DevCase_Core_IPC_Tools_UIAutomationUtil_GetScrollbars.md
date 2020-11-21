# UIAutomationUtil.GetScrollbars Method (Control)
 

Gets a value indicating which are the visible ScrollBars of a Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ScrollBars GetScrollbars(
	Control ctrl
)
```

**VB**<br />
``` VB
Public Shared Function GetScrollbars ( 
	ctrl As Control
) As ScrollBars
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim returnValue As ScrollBars

returnValue = UIAutomationUtil.GetScrollbars(ctrl)
```

**C++**<br />
``` C++
public:
static ScrollBars GetScrollbars(
	Control^ ctrl
)
```

**F#**<br />
``` F#
static member GetScrollbars : 
        ctrl : Control -> ScrollBars 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The control to retrieve their visible ScrollBars.</dd></dl>

#### Return Value
Type: ScrollBars<br />The visible ScrollBar(s).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim scrollBars As ScrollBars = GetScrollbars(TextBox1)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_GetScrollbars">GetScrollbars Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />