# GraphicalUtil.MouseIsOverControl Method 
 

Determinates whether the mouse pointer is inside the boundaries of a specified control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool MouseIsOverControl(
	Control ctrl
)
```

**VB**<br />
``` VB
Public Shared Function MouseIsOverControl ( 
	ctrl As Control
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim returnValue As Boolean

returnValue = GraphicalUtil.MouseIsOverControl(ctrl)
```

**C++**<br />
``` C++
public:
static bool MouseIsOverControl(
	Control^ ctrl
)
```

**F#**<br />
``` F#
static member MouseIsOverControl : 
        ctrl : Control -> bool 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The control.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the mouse pointer is inside the pixel range, `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isOverControl As Boolean = MouseIsOverControl(PictureBox1)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />