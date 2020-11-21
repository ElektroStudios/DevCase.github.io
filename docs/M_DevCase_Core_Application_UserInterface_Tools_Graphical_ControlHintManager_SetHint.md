# ControlHintManager.SetHint Method (Control, ControlHintInfo)
 

Sets a new control-hint for an specific control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetHint(
	Control ctrl,
	ControlHintInfo hintInfo
)
```

**VB**<br />
``` VB
Public Shared Sub SetHint ( 
	ctrl As Control,
	hintInfo As ControlHintInfo
)
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As Control
Dim hintInfo As ControlHintInfoControlHintManager.SetHint(ctrl, hintInfo)
```

**C++**<br />
``` C++
public:
static void SetHint(
	Control^ ctrl, 
	ControlHintInfo^ hintInfo
)
```

**F#**<br />
``` F#
static member SetHint : 
        ctrl : Control * 
        hintInfo : ControlHintInfo -> unit 

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: System.Windows.Forms.Control<br />The control.</dd><dt>hintInfo</dt><dd>Type: <a href="T_DevCase_Core_Application_UserInterface_ControlHintInfo">DevCase.Core.Application.UserInterface.ControlHintInfo</a><br />The text-hint properties.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Exception</td><td>control-hint text can't be null or empty.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlHintManager">ControlHintManager Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlHintManager_SetHint">SetHint Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />