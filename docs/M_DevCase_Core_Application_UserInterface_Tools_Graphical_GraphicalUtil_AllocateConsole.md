# GraphicalUtil.AllocateConsole Method 
 

Allocates a new console for the calling process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool AllocateConsole()
```

**VB**<br />
``` VB
Public Shared Function AllocateConsole As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = GraphicalUtil.AllocateConsole()
```

**C++**<br />
``` C++
public:
static bool AllocateConsole()
```

**F#**<br />
``` F#
static member AllocateConsole : unit -> bool 

```


#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Examples
This is a code example. 
**VB**<br />
``` VB
AllocateConsole()
Console.WriteLine("This is my console!")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />