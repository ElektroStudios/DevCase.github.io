# GraphicalUtil.IsFullscreen Method (Form)
 

Determine whether the specified form is running in fullscreen mode.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsFullscreen(
	Form form
)
```

**VB**<br />
``` VB
Public Shared Function IsFullscreen ( 
	form As Form
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim form As Form
Dim returnValue As Boolean

returnValue = GraphicalUtil.IsFullscreen(form)
```

**C++**<br />
``` C++
public:
static bool IsFullscreen(
	Form^ form
)
```

**F#**<br />
``` F#
static member IsFullscreen : 
        form : Form -> bool 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />\[Missing <param name="form"/> documentation for "M:DevCase.Core.Application.UserInterface.Tools.Graphical.GraphicalUtil.IsFullscreen(System.Windows.Forms.Form)"\]</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified form is running in fullscreen mode; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_IsFullscreen">IsFullscreen Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />