# FormDragger.FindFormDragInfo Method (Form)
 

Finds the <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a> instance that is associated with the specified Form.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FormDragInfo FindFormDragInfo(
	Form form
)
```

**VB**<br />
``` VB
Public Function FindFormDragInfo ( 
	form As Form
) As FormDragInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormDragger
Dim form As Form
Dim returnValue As FormDragInfo

returnValue = instance.FindFormDragInfo(form)
```

**C++**<br />
``` C++
public:
FormDragInfo^ FindFormDragInfo(
	Form^ form
)
```

**F#**<br />
``` F#
member FindFormDragInfo : 
        form : Form -> FormDragInfo 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The Form.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a><br />The <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a> instance that is associated with the specified Form.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_FormDragger">FormDragger Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_FormDragger_FindFormDragInfo">FindFormDragInfo Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />