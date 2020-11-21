# ControlIterator.PerformAction Method (Control.ControlCollection, Delegate, String)
 

Perform an operation on all the Controls on the specified Control Collection.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool PerformAction(
	Control.ControlCollection controlCollection,
	Delegate operation,
	string containsName = ""
)
```

**VB**<br />
``` VB
Public Shared Function PerformAction ( 
	controlCollection As Control.ControlCollection,
	operation As Delegate,
	Optional containsName As String = ""
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim controlCollection As Control.ControlCollection
Dim operation As [Delegate]
Dim containsName As String
Dim returnValue As Boolean

returnValue = ControlIterator.PerformAction(controlCollection, 
	operation, containsName)
```

**C++**<br />
``` C++
public:
static bool PerformAction(
	Control.ControlCollection^ controlCollection, 
	Delegate^ operation, 
	String^ containsName = L""
)
```

**F#**<br />
``` F#
static member PerformAction : 
        controlCollection : Control.ControlCollection * 
        operation : Delegate * 
        ?containsName : string 
(* Defaults:
        let _containsName = defaultArg containsName ""
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>controlCollection</dt><dd>Type: System.Windows.Forms.Control.ControlCollection<br />The control collection where to find the ctrls.</dd><dt>operation</dt><dd>Type: System.Delegate<br />The action to perform on the ctrl.</dd><dt>containsName (Optional)</dt><dd>Type: System.String<br />Indicates that only controls containing name should be collected.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operation succeeds; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator">ControlIterator Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_PerformAction">PerformAction Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />