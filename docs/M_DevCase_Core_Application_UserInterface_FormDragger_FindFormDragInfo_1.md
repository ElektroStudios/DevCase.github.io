# FormDragger.FindFormDragInfo Method (Control)
 

Finds the <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a> instance that is associated with the specified Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FormDragInfo FindFormDragInfo(
	Control ctrl
)
```

**VB**<br />
``` VB
Public Function FindFormDragInfo ( 
	ctrl As Control
) As FormDragInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormDragger
Dim ctrl As Control
Dim returnValue As FormDragInfo

returnValue = instance.FindFormDragInfo(ctrl)
```

**C++**<br />
``` C++
public:
FormDragInfo^ FindFormDragInfo(
	Control^ ctrl
)
```

**F#**<br />
``` F#
member FindFormDragInfo : 
        ctrl : Control -> FormDragInfo 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />A Control that is hosted by the Form.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a><br />The <a href="T_DevCase_Core_Application_UserInterface_FormDragInfo">FormDragInfo</a> instance that is associated with the specified Control.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_FormDragger">FormDragger Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_FormDragger_FindFormDragInfo">FindFormDragInfo Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />