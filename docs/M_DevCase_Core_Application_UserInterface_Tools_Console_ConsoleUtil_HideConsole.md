# ConsoleUtil.HideConsole Method 
 

Hides the console window associated with the calling process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool HideConsole()
```

**VB**<br />
``` VB
Public Shared Function HideConsole As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = ConsoleUtil.HideConsole()
```

**C++**<br />
``` C++
public:
static bool HideConsole()
```

**F#**<br />
``` F#
static member HideConsole : unit -> bool 

```


#### Return Value
Type: Boolean<br />If the window was previously visible, the return value is `true` (`True` in Visual Basic). 

 If the window was previously hidden, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />