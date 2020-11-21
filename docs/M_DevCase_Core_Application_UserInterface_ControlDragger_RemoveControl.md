# ControlDragger.RemoveControl Method 
 

Removes the specified Control from the draggable elements.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void RemoveControl(
	Control ctrl
)
```

**VB**<br />
``` VB
Public Sub RemoveControl ( 
	ctrl As Control
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlDragger
Dim ctrl As Control

instance.RemoveControl(ctrl)
```

**C++**<br />
``` C++
public:
void RemoveControl(
	Control^ ctrl
)
```

**F#**<br />
``` F#
member RemoveControl : 
        ctrl : Control -> unit 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The Control.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>The specified control is not found.;ctrl</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlDragger">ControlDragger Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />