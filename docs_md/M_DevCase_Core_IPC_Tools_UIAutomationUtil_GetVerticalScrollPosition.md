# UIAutomationUtil.GetVerticalScrollPosition Method (Control)
 

Gets the position of the Vertical scrollbar's scroll in a Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static VerticalScrollBarPosition GetVerticalScrollPosition(
	Control ctrl
)
```

**VB**<br />
``` VB
Public Shared Function GetVerticalScrollPosition ( 
	ctrl As Control
) As VerticalScrollBarPosition
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim returnValue As VerticalScrollBarPosition

returnValue = UIAutomationUtil.GetVerticalScrollPosition(ctrl)
```

**C++**<br />
``` C++
public:
static VerticalScrollBarPosition GetVerticalScrollPosition(
	Control^ ctrl
)
```

**F#**<br />
``` F#
static member GetVerticalScrollPosition : 
        ctrl : Control -> VerticalScrollBarPosition 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The Control.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_IPC_VerticalScrollBarPosition">VerticalScrollBarPosition</a><br />The scrollbar position.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim vScrollPos As VerticalScrollBarPosition = GetVerticalScrollPosition(RichTextBox1)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_GetVerticalScrollPosition">GetVerticalScrollPosition Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />