# UIAutomationUtil.IsHorizontalScrollVisible Method (Control)
 

Determines whether an Horizontal Scrollbar its shown in a Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsHorizontalScrollVisible(
	Control ctrl
)
```

**VB**<br />
``` VB
Public Shared Function IsHorizontalScrollVisible ( 
	ctrl As Control
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim returnValue As Boolean

returnValue = UIAutomationUtil.IsHorizontalScrollVisible(ctrl)
```

**C++**<br />
``` C++
public:
static bool IsHorizontalScrollVisible(
	Control^ ctrl
)
```

**F#**<br />
``` F#
static member IsHorizontalScrollVisible : 
        ctrl : Control -> bool 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The Control.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if vertical scrollbar its shown; otherwise, `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isHScrollBarVisible As Boolean = IsHorizontalScrollVisible(ListView1)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_IsHorizontalScrollVisible">IsHorizontalScrollVisible Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />