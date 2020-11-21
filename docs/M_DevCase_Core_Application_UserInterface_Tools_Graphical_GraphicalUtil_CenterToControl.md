# GraphicalUtil.CenterToControl Method 
 

Centers the bounds of a source Control to a target Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Point CenterToControl(
	Control source,
	Control target
)
```

**VB**<br />
``` VB
Public Shared Function CenterToControl ( 
	source As Control,
	target As Control
) As Point
```

**VB Usage**<br />
``` VB Usage
Dim source As Control
Dim target As Control
Dim returnValue As Point

returnValue = GraphicalUtil.CenterToControl(source, 
	target)
```

**C++**<br />
``` C++
public:
static Point CenterToControl(
	Control^ source, 
	Control^ target
)
```

**F#**<br />
``` F#
static member CenterToControl : 
        source : Control * 
        target : Control -> Point 

```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: System.Windows.Forms.Control<br />The source Control.</dd><dt>target</dt><dd>Type: System.Windows.Forms.Control<br />The target Control.</dd></dl>

#### Return Value
Type: Point<br />The new coordinates of the Control of the *source* parameter.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />