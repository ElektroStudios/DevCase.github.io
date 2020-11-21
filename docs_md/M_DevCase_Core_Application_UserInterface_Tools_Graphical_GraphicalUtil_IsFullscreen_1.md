# GraphicalUtil.IsFullscreen Method (IntPtr)
 

Determine whether the specified window is running in fullscreen mode.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsFullscreen(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
Public Shared Function IsFullscreen ( 
	hWnd As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim returnValue As Boolean

returnValue = GraphicalUtil.IsFullscreen(hWnd)
```

**C++**<br />
``` C++
public:
static bool IsFullscreen(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
static member IsFullscreen : 
        hWnd : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />\[Missing <param name="hWnd"/> documentation for "M:DevCase.Core.Application.UserInterface.Tools.Graphical.GraphicalUtil.IsFullscreen(System.IntPtr)"\]</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified window is running in fullscreen mode; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_IsFullscreen">IsFullscreen Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />