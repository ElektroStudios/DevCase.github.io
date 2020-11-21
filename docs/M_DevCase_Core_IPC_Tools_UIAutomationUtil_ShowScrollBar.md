# UIAutomationUtil.ShowScrollBar Method (Control, ScrollBars)
 

Shows the specified scrollbar of a Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ShowScrollBar(
	Control ctrl,
	ScrollBars scrollBars
)
```

**VB**<br />
``` VB
Public Shared Function ShowScrollBar ( 
	ctrl As Control,
	scrollBars As ScrollBars
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim scrollBars As ScrollBars
Dim returnValue As Boolean

returnValue = UIAutomationUtil.ShowScrollBar(ctrl, 
	scrollBars)
```

**C++**<br />
``` C++
public:
static bool ShowScrollBar(
	Control^ ctrl, 
	ScrollBars scrollBars
)
```

**F#**<br />
``` F#
static member ShowScrollBar : 
        ctrl : Control * 
        scrollBars : ScrollBars -> bool 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The Control.</dd><dt>scrollBars</dt><dd>Type: System.Windows.Forms.ScrollBars<br />The scrollbar(s) to be shown.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) If the function succeeds, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
ShowScrollBar(ListView1, ScrollBars.Both)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_ShowScrollBar">ShowScrollBar Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />