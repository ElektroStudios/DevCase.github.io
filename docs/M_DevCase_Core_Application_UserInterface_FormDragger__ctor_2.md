# FormDragger Constructor (Form, Boolean, Cursor)
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_UserInterface_FormDragger">FormDragger</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FormDragger(
	Form form,
	bool enabled = false,
	Cursor cursor = null
)
```

**VB**<br />
``` VB
Public Sub New ( 
	form As Form,
	Optional enabled As Boolean = false,
	Optional cursor As Cursor = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim form As Form
Dim enabled As Boolean
Dim cursor As Cursor

Dim instance As New FormDragger(form, enabled, 
	cursor)
```

**C++**<br />
``` C++
public:
FormDragger(
	Form^ form, 
	bool enabled = false, 
	Cursor^ cursor = nullptr
)
```

**F#**<br />
``` F#
new : 
        form : Form * 
        ?enabled : bool * 
        ?cursor : Cursor 
(* Defaults:
        let _enabled = defaultArg enabled false
        let _cursor = defaultArg cursor null
*)
-> FormDragger
```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The owner Form used to perform draggable operations.</dd><dt>enabled (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), inmediately enables dragging on the Form.</dd><dt>cursor (Optional)</dt><dd>Type: System.Windows.Forms.Cursor<br />The Cursor to use when dragging the Form.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_FormDragger">FormDragger Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_FormDragger__ctor">FormDragger Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />