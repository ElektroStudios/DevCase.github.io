# GraphicalUtil.Fade Method 
 

Fades in or fades out a Form.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Fade(
	Form form,
	FadingEffect effect,
	double ms,
	double opacity
)
```

**VB**<br />
``` VB
Public Shared Sub Fade ( 
	form As Form,
	effect As FadingEffect,
	ms As Double,
	opacity As Double
)
```

**VB Usage**<br />
``` VB Usage
Dim form As Form
Dim effect As FadingEffect
Dim ms As Double
Dim opacity As DoubleGraphicalUtil.Fade(form, effect, ms, opacity)
```

**C++**<br />
``` C++
public:
static void Fade(
	Form^ form, 
	FadingEffect effect, 
	double ms, 
	double opacity
)
```

**F#**<br />
``` F#
static member Fade : 
        form : Form * 
        effect : FadingEffect * 
        ms : float * 
        opacity : float -> unit 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The Form.</dd><dt>effect</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_FadingEffect">DevCase.Core.Application.UserInterface.FadingEffect</a><br />The fading effect.</dd><dt>ms</dt><dd>Type: System.Double<br />The time it takes to complete the fadiing effect, in milliseconds</dd><dt>opacity</dt><dd>Type: System.Double<br />The target form opacity.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />