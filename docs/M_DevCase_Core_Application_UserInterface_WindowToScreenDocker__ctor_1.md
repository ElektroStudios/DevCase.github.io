# WindowToScreenDocker Constructor (IWin32Window, Screen)
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_UserInterface_WindowToScreenDocker">WindowToScreenDocker</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public WindowToScreenDocker(
	IWin32Window window,
	Screen scr
)
```

**VB**<br />
``` VB
Public Sub New ( 
	window As IWin32Window,
	scr As Screen
)
```

**VB Usage**<br />
``` VB Usage
Dim window As IWin32Window
Dim scr As Screen

Dim instance As New WindowToScreenDocker(window, 
	scr)
```

**C++**<br />
``` C++
public:
WindowToScreenDocker(
	IWin32Window^ window, 
	Screen^ scr
)
```

**F#**<br />
``` F#
new : 
        window : IWin32Window * 
        scr : Screen -> WindowToScreenDocker
```


#### Parameters
&nbsp;<dl><dt>window</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The IWin32Window window that owns this instance (eg. a Form window).</dd><dt>scr</dt><dd>Type: System.Windows.Forms.Screen<br />The target <a href="P_DevCase_Core_Application_UserInterface_WindowToScreenDocker_Screen">Screen</a> where the docking will be performed.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_WindowToScreenDocker">WindowToScreenDocker Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_WindowToScreenDocker__ctor">WindowToScreenDocker Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />