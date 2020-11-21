# AppShellExecuteInfo.DontUseDesktopChangeRouter Property 
 

Gets or sets a value mandatory for debugger applications to avoid file dialog deadlocks when debugging the Windows Explorer process. 

 Setting the DontUseDesktopChangeRouter entry produces a slightly less efficient handling of the change notifications, however.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool DontUseDesktopChangeRouter { get; set; }
```

**VB**<br />
``` VB
Public Property DontUseDesktopChangeRouter As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppShellExecuteInfo
Dim value As Boolean

value = instance.DontUseDesktopChangeRouter

instance.DontUseDesktopChangeRouter = value
```

**C++**<br />
``` C++
public:
property bool DontUseDesktopChangeRouter {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member DontUseDesktopChangeRouter : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the application avoids file dialog deadlocks when debugging the Windows Explorer process; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppShellExecuteInfo">AppShellExecuteInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />