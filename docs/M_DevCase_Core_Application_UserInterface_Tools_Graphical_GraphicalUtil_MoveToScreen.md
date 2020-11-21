# GraphicalUtil.MoveToScreen Method 
 

Moves the specified Control (normally a Form) to the target screen.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Point MoveToScreen(
	Control ctrl,
	Screen display
)
```

**VB**<br />
``` VB
Public Shared Function MoveToScreen ( 
	ctrl As Control,
	display As Screen
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim display As Screen
Dim returnValue As Point

returnValue = GraphicalUtil.MoveToScreen(ctrl, 
	display)
```

**C++**<br />
``` C++
public:
static Point MoveToScreen(
	Control^ ctrl, 
	Screen^ display
)
```

**F#**<br />
``` F#
static member MoveToScreen : 
        ctrl : Control * 
        display : Screen -> Point 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The source Control.</dd><dt>display</dt><dd>Type: System.Windows.Forms.Screen<br />The target screen.</dd></dl>

#### Return Value
Type: Point<br />The new coordinates of the source Control.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />