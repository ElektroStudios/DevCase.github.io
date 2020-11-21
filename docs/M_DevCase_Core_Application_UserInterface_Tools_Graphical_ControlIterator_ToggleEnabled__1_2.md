# ControlIterator.ToggleEnabled(*T*) Method (Control.ControlCollection, String)
 

Toggle the enabled state of all the Controls of the specified Type on the specified Control Collection.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ToggleEnabled<T>(
	Control.ControlCollection controlCollection,
	string containsName = ""
)
where T : Control

```

**VB**<br />
``` VB
Public Shared Function ToggleEnabled(Of T As Control) ( 
	controlCollection As Control.ControlCollection,
	Optional containsName As String = ""
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim controlCollection As Control.ControlCollection
Dim containsName As String
Dim returnValue As Boolean

returnValue = ControlIterator.ToggleEnabled(controlCollection, 
	containsName)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : Control
static bool ToggleEnabled(
	Control.ControlCollection^ controlCollection, 
	String^ containsName = L""
)
```

**F#**<br />
``` F#
static member ToggleEnabled : 
        controlCollection : Control.ControlCollection * 
        ?containsName : string 
(* Defaults:
        let _containsName = defaultArg containsName ""
*)
-> bool  when 'T : Control

```


#### Parameters
&nbsp;<dl><dt>controlCollection</dt><dd>Type: System.Windows.Forms.Control.ControlCollection<br />The control collection where to find the ctrls.</dd><dt>containsName (Optional)</dt><dd>Type: System.String<br />Indicates that only controls containing name should be collected.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of control.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operation succeeds; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator">ControlIterator Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleEnabled">ToggleEnabled Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />