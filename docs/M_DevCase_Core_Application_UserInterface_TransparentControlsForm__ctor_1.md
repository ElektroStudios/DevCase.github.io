# TransparentControlsForm Constructor (Control[], Point)
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_UserInterface_TransparentControlsForm">TransparentControlsForm</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public TransparentControlsForm(
	Control[] controls,
	Point formLocation = null
)
```

**VB**<br />
``` VB
Public Sub New ( 
	controls As Control(),
	Optional formLocation As Point = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim controls As Control()
Dim formLocation As Point

Dim instance As New TransparentControlsForm(controls, 
	formLocation)
```

**C++**<br />
``` C++
public:
TransparentControlsForm(
	array<Control^>^ controls, 
	Point formLocation = nullptr
)
```

**F#**<br />
``` F#
new : 
        controls : Control[] * 
        ?formLocation : Point 
(* Defaults:
        let _formLocation = defaultArg formLocation null
*)
-> TransparentControlsForm
```


#### Parameters
&nbsp;<dl><dt>controls</dt><dd>Type: System.Windows.Forms.Control[]<br />The control array to display in the Form.</dd><dt>formLocation (Optional)</dt><dd>Type: System.Drawing.Point<br />The default Formulary location.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_TransparentControlsForm">TransparentControlsForm Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_TransparentControlsForm__ctor">TransparentControlsForm Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />