# FormDragger.AddControl Method 
 

Assigns the specified Control as a draggable element.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void AddControl(
	Control ctrl
)
```

**VB**<br />
``` VB
Public Sub AddControl ( 
	ctrl As Control
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormDragger
Dim ctrl As Control

instance.AddControl(ctrl)
```

**C++**<br />
``` C++
public:
void AddControl(
	Control^ ctrl
)
```

**F#**<br />
``` F#
member AddControl : 
        ctrl : Control -> unit 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The Control.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>The parent form of the control is not handled.;ctrl</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_FormDragger">FormDragger Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />