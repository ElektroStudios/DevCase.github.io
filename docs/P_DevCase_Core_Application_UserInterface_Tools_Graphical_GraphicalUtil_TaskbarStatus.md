# GraphicalUtil.TaskbarStatus Property 
 

Gets or sets the Taskbar status of the current application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static TaskbarProgressBarState TaskbarStatus { get; set; }
```

**VB**<br />
``` VB
Public Shared Property TaskbarStatus As TaskbarProgressBarState
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As TaskbarProgressBarState

value = GraphicalUtil.TaskbarStatus

GraphicalUtil.TaskbarStatus = value
```

**C++**<br />
``` C++
public:
static property TaskbarProgressBarState TaskbarStatus {
	TaskbarProgressBarState get ();
	void set (TaskbarProgressBarState value);
}
```

**F#**<br />
``` F#
static member TaskbarStatus : TaskbarProgressBarState with get, set

```


#### Property Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TaskbarProgressBarState">TaskbarProgressBarState</a><br />The Taskbar status of the current application.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />