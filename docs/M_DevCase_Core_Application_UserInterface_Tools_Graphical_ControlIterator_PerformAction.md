# ControlIterator.PerformAction Method (IEnumerable(Control), Delegate)
 

Perform an operation on multiple Controls at once.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool PerformAction(
	IEnumerable<Control> ctrls,
	Delegate operation
)
```

**VB**<br />
``` VB
Public Shared Function PerformAction ( 
	ctrls As IEnumerable(Of Control),
	operation As Delegate
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim ctrls As IEnumerable(Of Control)
Dim operation As [Delegate]
Dim returnValue As Boolean

returnValue = ControlIterator.PerformAction(ctrls, 
	operation)
```

**C++**<br />
``` C++
public:
static bool PerformAction(
	IEnumerable<Control^>^ ctrls, 
	Delegate^ operation
)
```

**F#**<br />
``` F#
static member PerformAction : 
        ctrls : IEnumerable<Control> * 
        operation : Delegate -> bool 

```


#### Parameters
&nbsp;<dl><dt>ctrls</dt><dd>Type: System.Collections.Generic.IEnumerable(Control)<br />The controls to perform the Action.</dd><dt>operation</dt><dd>Type: System.Delegate<br />The action to perform on the ctrl.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operation succeeds; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator">ControlIterator Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_PerformAction">PerformAction Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />