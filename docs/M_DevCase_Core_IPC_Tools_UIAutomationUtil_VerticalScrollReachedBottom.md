# UIAutomationUtil.VerticalScrollReachedBottom Method (Control)
 

Determines whether the Vertical Scrollbar's scroll of a Control has reached the Bottom of the Scroll range.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool VerticalScrollReachedBottom(
	Control ctrl
)
```

**VB**<br />
``` VB
Public Shared Function VerticalScrollReachedBottom ( 
	ctrl As Control
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim returnValue As Boolean

returnValue = UIAutomationUtil.VerticalScrollReachedBottom(ctrl)
```

**C++**<br />
``` C++
public:
static bool VerticalScrollReachedBottom(
	Control^ ctrl
)
```

**F#**<br />
``` F#
static member VerticalScrollReachedBottom : 
        ctrl : Control -> bool 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The Control.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the Vertical Scrollbar's scroll has reached the Bottom of the Scroll range, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="Overload_DevCase_Core_IPC_Tools_UIAutomationUtil_VerticalScrollReachedBottom">VerticalScrollReachedBottom Overload</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />