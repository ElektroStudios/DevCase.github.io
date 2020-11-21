# UIAutomationUtil.GetVerticalScrollPosition Method (IWin32Window)
 

Gets the position of the Vertical scrollbar's scroll in a window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static VerticalScrollBarPosition GetVerticalScrollPosition(
	IWin32Window window
)
```

**VB**<br />
``` VB
Public Shared Function GetVerticalScrollPosition ( 
	window As IWin32Window
) As VerticalScrollBarPosition
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim returnValue As VerticalScrollBarPosition

returnValue = UIAutomationUtil.GetVerticalScrollPosition(window)
```

**C++**<br />
``` C++
public:
static VerticalScrollBarPosition GetVerticalScrollPosition(
	IWin32Window^ window
)
```

**F#**<br />
``` F#
static member GetVerticalScrollPosition : 
        window : IWin32Window -> VerticalScrollBarPosition 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_IPC_VerticalScrollBarPosition">VerticalScrollBarPosition</a><br />The scrollbar position.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim vScrollPos As VerticalScrollBarPosition = GetVerticalScrollPosition(window)
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_GetVerticalScrollPosition">GetVerticalScrollPosition Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />