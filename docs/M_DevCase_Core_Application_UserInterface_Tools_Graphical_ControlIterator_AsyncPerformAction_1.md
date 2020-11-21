# ControlIterator.AsyncPerformAction Method (Control, Delegate)
 

Perform an asynchronous operation on a specific ctrl.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool AsyncPerformAction(
	Control ctrl,
	Delegate operation
)
```

**VB**<br />
``` VB
Public Shared Function AsyncPerformAction ( 
	ctrl As Control,
	operation As Delegate
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim operation As [Delegate]
Dim returnValue As Boolean

returnValue = ControlIterator.AsyncPerformAction(ctrl, 
	operation)
```

**C++**<br />
``` C++
public:
static bool AsyncPerformAction(
	Control^ ctrl, 
	Delegate^ operation
)
```

**F#**<br />
``` F#
static member AsyncPerformAction : 
        ctrl : Control * 
        operation : Delegate -> bool 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The control to perform the Action.</dd><dt>operation</dt><dd>Type: System.Delegate<br />The action to perform on the ctrl.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operation succeeds; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator">ControlIterator Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncPerformAction">AsyncPerformAction Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />