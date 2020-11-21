# FormDragger.AddControls Method 
 

Assigns the specified controls as draggable elements of they parents Form.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void AddControls(
	Control[] ctrls
)
```

**VB**<br />
``` VB
Public Sub AddControls ( 
	ctrls As Control()
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormDragger
Dim ctrls As Control()

instance.AddControls(ctrls)
```

**C++**<br />
``` C++
public:
void AddControls(
	array<Control^>^ ctrls
)
```

**F#**<br />
``` F#
member AddControls : 
        ctrls : Control[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>ctrls</dt><dd>Type: System.Windows.Forms.Control[]<br />An array of Control.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>The parent form of the control is not handled.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_FormDragger">FormDragger Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />