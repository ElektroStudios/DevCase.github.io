# FormDragger.FindFormDragInfo Method (String, StringComparison)
 

Finds the <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a> instance that is associated with the specified Form.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FormDragInfo FindFormDragInfo(
	string formName,
	StringComparison stringComparison = StringComparison.OrdinalIgnoreCase
)
```

**VB**<br />
``` VB
Public Function FindFormDragInfo ( 
	formName As String,
	Optional stringComparison As StringComparison = StringComparison.OrdinalIgnoreCase
) As FormDragInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormDragger
Dim formName As String
Dim stringComparison As StringComparison
Dim returnValue As FormDragInfo

returnValue = instance.FindFormDragInfo(formName, 
	stringComparison)
```

**C++**<br />
``` C++
public:
FormDragInfo^ FindFormDragInfo(
	String^ formName, 
	StringComparison stringComparison = StringComparison::OrdinalIgnoreCase
)
```

**F#**<br />
``` F#
member FindFormDragInfo : 
        formName : string * 
        ?stringComparison : StringComparison 
(* Defaults:
        let _stringComparison = defaultArg stringComparison StringComparison.OrdinalIgnoreCase
*)
-> FormDragInfo 

```


#### Parameters
&nbsp;<dl><dt>formName</dt><dd>Type: System.String<br />The name of the Form.</dd><dt>stringComparison (Optional)</dt><dd>Type: System.StringComparison<br />\[Missing <param name="stringComparison"/> documentation for "M:DevCase.Core.Application.UserInterface.FormDragger.FindFormDragInfo(System.String,System.StringComparison)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a><br />The <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a> instance that is associated with the specified Form .

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_FormDragger">FormDragger Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_FormDragger_FindFormDragInfo">FindFormDragInfo Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />