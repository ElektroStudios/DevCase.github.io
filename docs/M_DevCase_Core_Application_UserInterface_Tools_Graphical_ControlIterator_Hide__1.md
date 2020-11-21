# ControlIterator.Hide(*T*) Method (String)
 

Hide all the Controls of the specified Type on the active Formulary.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool Hide<T>(
	string containsName = ""
)
where T : Control

```

**VB**<br />
``` VB
Public Shared Function Hide(Of T As Control) ( 
	Optional containsName As String = ""
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim containsName As String
Dim returnValue As Boolean

returnValue = ControlIterator.Hide(containsName)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : Control
static bool Hide(
	String^ containsName = L""
)
```

**F#**<br />
``` F#
static member Hide : 
        ?containsName : string 
(* Defaults:
        let _containsName = defaultArg containsName ""
*)
-> bool  when 'T : Control

```


#### Parameters
&nbsp;<dl><dt>containsName (Optional)</dt><dd>Type: System.String<br />Indicates that only controls containing name should be collected.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of control.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operation succeeds; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator">ControlIterator Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Hide">Hide Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />