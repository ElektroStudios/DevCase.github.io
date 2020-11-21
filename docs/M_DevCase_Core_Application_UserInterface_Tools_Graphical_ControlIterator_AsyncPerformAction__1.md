# ControlIterator.AsyncPerformAction(*T*) Method (Delegate, String)
 

Perform an asynchronous operation on all the Controls of the specified Type on the active Formulary.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool AsyncPerformAction<T>(
	Delegate operation,
	string containsName = ""
)
where T : Control

```

**VB**<br />
``` VB
Public Shared Function AsyncPerformAction(Of T As Control) ( 
	operation As Delegate,
	Optional containsName As String = ""
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim operation As [Delegate]
Dim containsName As String
Dim returnValue As Boolean

returnValue = ControlIterator.AsyncPerformAction(operation, 
	containsName)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : Control
static bool AsyncPerformAction(
	Delegate^ operation, 
	String^ containsName = L""
)
```

**F#**<br />
``` F#
static member AsyncPerformAction : 
        operation : Delegate * 
        ?containsName : string 
(* Defaults:
        let _containsName = defaultArg containsName ""
*)
-> bool  when 'T : Control

```


#### Parameters
&nbsp;<dl><dt>operation</dt><dd>Type: System.Delegate<br />\[Missing <param name="operation"/> documentation for "M:DevCase.Core.Application.UserInterface.Tools.Graphical.ControlIterator.AsyncPerformAction``1(System.Delegate,System.String)"\]</dd><dt>containsName (Optional)</dt><dd>Type: System.String<br />Indicates that only controls containing name should be collected.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of control.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operation succeeds; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator">ControlIterator Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncPerformAction">AsyncPerformAction Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />