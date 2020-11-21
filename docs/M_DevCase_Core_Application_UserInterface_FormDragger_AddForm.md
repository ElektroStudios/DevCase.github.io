# FormDragger.AddForm Method 
 

Assigns the specified Form as a draggable element.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void AddForm(
	Form form,
	bool enabled = false,
	Cursor cursor = null
)
```

**VB**<br />
``` VB
Public Sub AddForm ( 
	form As Form,
	Optional enabled As Boolean = false,
	Optional cursor As Cursor = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormDragger
Dim form As Form
Dim enabled As Boolean
Dim cursor As Cursor

instance.AddForm(form, enabled, cursor)
```

**C++**<br />
``` C++
public:
void AddForm(
	Form^ form, 
	bool enabled = false, 
	Cursor^ cursor = nullptr
)
```

**F#**<br />
``` F#
member AddForm : 
        form : Form * 
        ?enabled : bool * 
        ?cursor : Cursor 
(* Defaults:
        let _enabled = defaultArg enabled false
        let _cursor = defaultArg cursor null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The Form.</dd><dt>enabled (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), inmediatelly enables dragging on the Form.</dd><dt>cursor (Optional)</dt><dd>Type: System.Windows.Forms.Cursor<br />The Cursor to use when dragging the Form.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>The specified form is already added.;form</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_FormDragger">FormDragger Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />