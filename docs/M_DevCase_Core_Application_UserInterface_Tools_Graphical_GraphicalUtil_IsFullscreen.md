# GraphicalUtil.IsFullscreen Method (Process)
 

Determine whether the specified process is running in fullscreen mode.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsFullscreen(
	Process p
)
```

**VB**<br />
``` VB
Public Shared Function IsFullscreen ( 
	p As Process
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim p As Process
Dim returnValue As Boolean

returnValue = GraphicalUtil.IsFullscreen(p)
```

**C++**<br />
``` C++
public:
static bool IsFullscreen(
	Process^ p
)
```

**F#**<br />
``` F#
static member IsFullscreen : 
        p : Process -> bool 

```


#### Parameters
&nbsp;<dl><dt>p</dt><dd>Type: System.Diagnostics.Process<br />\[Missing <param name="p"/> documentation for "M:DevCase.Core.Application.UserInterface.Tools.Graphical.GraphicalUtil.IsFullscreen(System.Diagnostics.Process)"\]</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified process is running in fullscreen mode; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_IsFullscreen">IsFullscreen Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />