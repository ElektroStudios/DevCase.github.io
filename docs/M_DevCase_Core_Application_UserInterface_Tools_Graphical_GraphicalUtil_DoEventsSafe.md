# GraphicalUtil.DoEventsSafe Method 
 

Processes all Windows messages currently in the message queue of the GUI. 

 This method greatly boosts the performance of any application in difference to DoEvents() method. 

 When calling DoEvents() to make the UI responsive, it generally decreases application performance; 

 however, using this method, we make sure there is at least one input event (keyboard or mouse) that needs to be processed before internally calling DoEvents().

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void DoEventsSafe()
```

**VB**<br />
``` VB
Public Shared Sub DoEventsSafe
```

**VB Usage**<br />
``` VB Usage

GraphicalUtil.DoEventsSafe()
```

**C++**<br />
``` C++
public:
static void DoEventsSafe()
```

**F#**<br />
``` F#
static member DoEventsSafe : unit -> unit 

```


## Examples
This is a code example. 
**VB**<br />
``` VB
Do While True
    DoEvents()
Loop
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />