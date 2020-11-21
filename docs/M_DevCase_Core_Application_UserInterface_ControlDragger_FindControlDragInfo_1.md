# ControlDragger.FindControlDragInfo Method (Control)
 

Finds the <a href="T_DevCase_Core_Application_UserInterface_ControlDragInfo">ControlDragInfo</a> instance that is associated with the specified Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ControlDragInfo FindControlDragInfo(
	Control ctrl
)
```

**VB**<br />
``` VB
Public Function FindControlDragInfo ( 
	ctrl As Control
) As ControlDragInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlDragger
Dim ctrl As Control
Dim returnValue As ControlDragInfo

returnValue = instance.FindControlDragInfo(ctrl)
```

**C++**<br />
``` C++
public:
ControlDragInfo^ FindControlDragInfo(
	Control^ ctrl
)
```

**F#**<br />
``` F#
member FindControlDragInfo : 
        ctrl : Control -> ControlDragInfo 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The Control.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Application_UserInterface_ControlDragInfo">ControlDragInfo</a><br />The <a href="T_DevCase_Core_Application_UserInterface_ControlDragInfo">ControlDragInfo</a> instance that is associated with the specified Control.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlDragger">ControlDragger Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_ControlDragger_FindControlDragInfo">FindControlDragInfo Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />