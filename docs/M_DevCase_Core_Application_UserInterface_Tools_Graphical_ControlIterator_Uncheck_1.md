# ControlIterator.Uncheck Method (Control)
 

Uncheck an specific ctrl.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool Uncheck(
	Control ctrl
)
```

**VB**<br />
``` VB
Public Shared Function Uncheck ( 
	ctrl As Control
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim returnValue As Boolean

returnValue = ControlIterator.Uncheck(ctrl)
```

**C++**<br />
``` C++
public:
static bool Uncheck(
	Control^ ctrl
)
```

**F#**<br />
``` F#
static member Uncheck : 
        ctrl : Control -> bool 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The control to uncheck.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operation succeeds; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator">ControlIterator Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Uncheck">Uncheck Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />