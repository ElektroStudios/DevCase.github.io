# ControlDragger Constructor (Control, Boolean, Cursor)
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_UserInterface_ControlDragger">ControlDragger</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ControlDragger(
	Control ctrl,
	bool enabled = false,
	Cursor cursor = null
)
```

**VB**<br />
``` VB
Public Sub New ( 
	ctrl As Control,
	Optional enabled As Boolean = false,
	Optional cursor As Cursor = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim enabled As Boolean
Dim cursor As Cursor

Dim instance As New ControlDragger(ctrl, enabled, 
	cursor)
```

**C++**<br />
``` C++
public:
ControlDragger(
	Control^ ctrl, 
	bool enabled = false, 
	Cursor^ cursor = nullptr
)
```

**F#**<br />
``` F#
new : 
        ctrl : Control * 
        ?enabled : bool * 
        ?cursor : Cursor 
(* Defaults:
        let _enabled = defaultArg enabled false
        let _cursor = defaultArg cursor null
*)
-> ControlDragger
```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The owner Control used to perform draggable operations.</dd><dt>enabled (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), inmediately enables dragging on the Control.</dd><dt>cursor (Optional)</dt><dd>Type: System.Windows.Forms.Cursor<br />The Cursor to use when dragging the Control.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlDragger">ControlDragger Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_ControlDragger__ctor">ControlDragger Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />