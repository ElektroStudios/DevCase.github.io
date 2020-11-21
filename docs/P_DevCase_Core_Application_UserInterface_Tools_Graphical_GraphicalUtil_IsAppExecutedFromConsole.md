# GraphicalUtil.IsAppExecutedFromConsole Property 
 

Gets a value indicating whether the user has executed the current application from the Windows CMD.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsAppExecutedFromConsole { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property IsAppExecutedFromConsole As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Boolean

value = GraphicalUtil.IsAppExecutedFromConsole

```

**C++**<br />
``` C++
public:
static property bool IsAppExecutedFromConsole {
	bool get ();
}
```

**F#**<br />
``` F#
static member IsAppExecutedFromConsole : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the user has executed the current application from the Windows CMD; otherwise, `false` (`False` in Visual Basic). 

 If the parent cmd.exe process has exited before calling IsAppExecutedFromConsole, return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />