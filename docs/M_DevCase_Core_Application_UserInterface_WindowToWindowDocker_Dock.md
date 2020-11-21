# WindowToWindowDocker.Dock Method 
 

Docks the window to a specified position.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Dock(
	IWin32Window targetWindow,
	WindowDockingPosition position
)
```

**VB**<br />
``` VB
Public Overridable Sub Dock ( 
	targetWindow As IWin32Window,
	position As WindowDockingPosition
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowToWindowDocker
Dim targetWindow As IWin32Window
Dim position As WindowDockingPosition

instance.Dock(targetWindow, position)
```

**C++**<br />
``` C++
public:
virtual void Dock(
	IWin32Window^ targetWindow, 
	WindowDockingPosition position
)
```

**F#**<br />
``` F#
abstract Dock : 
        targetWindow : IWin32Window * 
        position : WindowDockingPosition -> unit 
override Dock : 
        targetWindow : IWin32Window * 
        position : WindowDockingPosition -> unit 
```


#### Parameters
&nbsp;<dl><dt>targetWindow</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The target window where to perform the docking.</dd><dt>position</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_WindowDockingPosition">DevCase.Core.Application.UserInterface.WindowDockingPosition</a><br />The target docking position.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_WindowToWindowDocker">WindowToWindowDocker Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />