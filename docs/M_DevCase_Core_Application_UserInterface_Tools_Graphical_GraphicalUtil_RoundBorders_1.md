# GraphicalUtil.RoundBorders Method (Form, Int32)
 

Rounds the borders of a Form. 

 Note that the FormBorderStyle form's property should be set to None.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RoundBorders(
	Form form,
	int radius
)
```

**VB**<br />
``` VB
Public Shared Sub RoundBorders ( 
	form As Form,
	radius As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim form As Form
Dim radius As Integer

GraphicalUtil.RoundBorders(form, radius)
```

**C++**<br />
``` C++
public:
static void RoundBorders(
	Form^ form, 
	int radius
)
```

**F#**<br />
``` F#
static member RoundBorders : 
        form : Form * 
        radius : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The Form.</dd><dt>radius</dt><dd>Type: System.Int32<br />The rounding radius.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim f As Form = Me
f.FormBorderStyle = Windows.Forms.FormBorderStyle.None
RoundBorders(f, 20)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil_RoundBorders">RoundBorders Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />