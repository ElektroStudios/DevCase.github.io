# ControlHintManager.SetHint Method (Control[], ControlHintInfo)
 

Sets a new control-hint for multiple controls at once.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetHint(
	Control[] controls,
	ControlHintInfo hintInfo
)
```

**VB**<br />
``` VB
Public Shared Sub SetHint ( 
	controls As Control(),
	hintInfo As ControlHintInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim controls As Control()
Dim hintInfo As ControlHintInfoControlHintManager.SetHint(controls, hintInfo)
```

**C++**<br />
``` C++
public:
static void SetHint(
	array<Control^>^ controls, 
	ControlHintInfo^ hintInfo
)
```

**F#**<br />
``` F#
static member SetHint : 
        controls : Control[] * 
        hintInfo : ControlHintInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>controls</dt><dd>Type: System.Windows.Forms.Control[]<br />The controls.</dd><dt>hintInfo</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_ControlHintInfo">DevCase.Core.Application.UserInterface.ControlHintInfo</a><br />The control-hint properties.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlHintManager">ControlHintManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlHintManager_SetHint">SetHint Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />