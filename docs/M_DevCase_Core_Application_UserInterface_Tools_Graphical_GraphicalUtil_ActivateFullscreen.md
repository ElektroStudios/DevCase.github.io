# GraphicalUtil.ActivateFullscreen Method 
 

Cause the specified Form to enter in Fullscreen mode.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ActivateFullscreen(
	Form form,
	bool topMost = true
)
```

**VB**<br />
``` VB
Public Shared Sub ActivateFullscreen ( 
	form As Form,
	Optional topMost As Boolean = true
)
```

**VB Usage**<br />
``` VB Usage
Dim form As Form
Dim topMost As BooleanGraphicalUtil.ActivateFullscreen(form, topMost)
```

**C++**<br />
``` C++
public:
static void ActivateFullscreen(
	Form^ form, 
	bool topMost = true
)
```

**F#**<br />
``` F#
static member ActivateFullscreen : 
        form : Form * 
        ?topMost : bool 
(* Defaults:
        let _topMost = defaultArg topMost true
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>form</dt><dd>Type: System.Windows.Forms.Form<br />The target Form.</dd><dt>topMost (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), causes the target Form to be the top-most window. 

 Default value is `true` (`True` in Visual Basic).</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
ActivateFullScreen(Me, topMost:=True)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />