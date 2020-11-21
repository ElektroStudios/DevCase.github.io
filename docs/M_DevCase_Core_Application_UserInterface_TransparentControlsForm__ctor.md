# TransparentControlsForm Constructor (Control, Point)
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_UserInterface_TransparentControlsForm">TransparentControlsForm</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public TransparentControlsForm(
	Control control,
	Point formLocation = null
)
```

**VB**<br />
``` VB
Public Sub New ( 
	control As Control,
	Optional formLocation As Point = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim control As Control
Dim formLocation As Point

Dim instance As New TransparentControlsForm(control, 
	formLocation)
```

**C++**<br />
``` C++
public:
TransparentControlsForm(
	Control^ control, 
	Point formLocation = nullptr
)
```

**F#**<br />
``` F#
new : 
        control : Control * 
        ?formLocation : Point 
(* Defaults:
        let _formLocation = defaultArg formLocation null
*)
-> TransparentControlsForm
```


#### Parameters
&nbsp;<dl><dt>control</dt><dd>Type: System.Windows.Forms.Control<br />The control to display in the Formulary.</dd><dt>formLocation (Optional)</dt><dd>Type: System.Drawing.Point<br />The default Formulary location.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_TransparentControlsForm">TransparentControlsForm Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_TransparentControlsForm__ctor">TransparentControlsForm Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />