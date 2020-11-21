# ControlDragger.AddControl Method 
 

Assigns the specified Control as a draggable element.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void AddControl(
	Control ctrl,
	bool enabled = false,
	Cursor cursor = null
)
```

**VB**<br />
``` VB
Public Sub AddControl ( 
	ctrl As Control,
	Optional enabled As Boolean = false,
	Optional cursor As Cursor = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlDragger
Dim ctrl As Control
Dim enabled As Boolean
Dim cursor As Cursor

instance.AddControl(ctrl, enabled, cursor)
```

**C++**<br />
``` C++
public:
void AddControl(
	Control^ ctrl, 
	bool enabled = false, 
	Cursor^ cursor = nullptr
)
```

**F#**<br />
``` F#
member AddControl : 
        ctrl : Control * 
        ?enabled : bool * 
        ?cursor : Cursor 
(* Defaults:
        let _enabled = defaultArg enabled false
        let _cursor = defaultArg cursor null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The Control.</dd><dt>enabled (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), inmediatelly enables dragging on the Control.</dd><dt>cursor (Optional)</dt><dd>Type: System.Windows.Forms.Cursor<br />The Cursor to use when dragging the Control.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>The specified control is already added.;ctrl</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlDragger">ControlDragger Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />