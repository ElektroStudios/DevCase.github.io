# UIAutomationUtil.VerticalScrollReachedTop Method (IWin32Window)
 

Determines whether the Vertical Scrollbar's scroll of a window has reached the Top of the Scroll range.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool VerticalScrollReachedTop(
	IWin32Window window
)
```

**VB**<br />
``` VB
Public Shared Function VerticalScrollReachedTop ( 
	window As IWin32Window
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim returnValue As Boolean

returnValue = UIAutomationUtil.VerticalScrollReachedTop(window)
```

**C++**<br />
``` C++
public:
static bool VerticalScrollReachedTop(
	IWin32Window^ window
)
```

**F#**<br />
``` F#
static member VerticalScrollReachedTop : 
        window : IWin32Window -> bool 

```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The window.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the Vertical Scrollbar's scroll has reached the Top of the Scroll range, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_VerticalScrollReachedTop">VerticalScrollReachedTop Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />