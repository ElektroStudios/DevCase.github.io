# ControlIterator.AsyncToggleVisible(*T*) Method (Control, String)
 

Asynchronously Toggle the visible state of all the Controls of the specified Type on the specified Control Container.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool AsyncToggleVisible<T>(
	Control controlContainer,
	string containsName = ""
)
where T : Control

```

**VB**<br />
``` VB
Public Shared Function AsyncToggleVisible(Of T As Control) ( 
	controlContainer As Control,
	Optional containsName As String = ""
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim controlContainer As Control
Dim containsName As String
Dim returnValue As Boolean

returnValue = ControlIterator.AsyncToggleVisible(controlContainer, 
	containsName)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : Control
static bool AsyncToggleVisible(
	Control^ controlContainer, 
	String^ containsName = L""
)
```

**F#**<br />
``` F#
static member AsyncToggleVisible : 
        controlContainer : Control * 
        ?containsName : string 
(* Defaults:
        let _containsName = defaultArg containsName ""
*)
-> bool  when 'T : Control

```


#### Parameters
&nbsp;<dl><dt>controlContainer</dt><dd>Type: System.Windows.Forms.Control<br />The control container where to find the ctrls.</dd><dt>containsName (Optional)</dt><dd>Type: System.String<br />Indicates that only controls containing name should be collected.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of control.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operation succeeds; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator">ControlIterator Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleVisible">AsyncToggleVisible Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />