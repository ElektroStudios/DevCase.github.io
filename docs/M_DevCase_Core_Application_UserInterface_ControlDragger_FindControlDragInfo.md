# ControlDragger.FindControlDragInfo Method (String, StringComparison)
 

Finds the <a href="T_DevCase_Core_Application_UserInterface_ControlDragInfo">ControlDragInfo</a> instance that is associated with the specified Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ControlDragInfo FindControlDragInfo(
	string controlName,
	StringComparison stringComparison = StringComparison.OrdinalIgnoreCase
)
```

**VB**<br />
``` VB
Public Function FindControlDragInfo ( 
	controlName As String,
	Optional stringComparison As StringComparison = StringComparison.OrdinalIgnoreCase
) As ControlDragInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlDragger
Dim controlName As String
Dim stringComparison As StringComparison
Dim returnValue As ControlDragInfo

returnValue = instance.FindControlDragInfo(controlName, 
	stringComparison)
```

**C++**<br />
``` C++
public:
ControlDragInfo^ FindControlDragInfo(
	String^ controlName, 
	StringComparison stringComparison = StringComparison::OrdinalIgnoreCase
)
```

**F#**<br />
``` F#
member FindControlDragInfo : 
        controlName : string * 
        ?stringComparison : StringComparison 
(* Defaults:
        let _stringComparison = defaultArg stringComparison StringComparison.OrdinalIgnoreCase
*)
-> ControlDragInfo 

```


#### Parameters
&nbsp;<dl><dt>controlName</dt><dd>Type: System.String<br />The name of the Control.</dd><dt>stringComparison (Optional)</dt><dd>Type: System.StringComparison<br />\[Missing <param name="stringComparison"/> documentation for "M:DevCase.Core.Application.UserInterface.ControlDragger.FindControlDragInfo(System.String,System.StringComparison)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Application_UserInterface_ControlDragInfo">ControlDragInfo</a><br />The <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a> instance that is associated with the specified Control .

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlDragger">ControlDragger Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_ControlDragger_FindControlDragInfo">FindControlDragInfo Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />