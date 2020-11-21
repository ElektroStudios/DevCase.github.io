# ControlHintManager.ControlHints Property 
 

Gets the control-hints that has been created.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Dictionary<Control, ControlHintInfo> ControlHints { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ControlHints As Dictionary(Of Control, ControlHintInfo)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Dictionary(Of Control, ControlHintInfo)

value = ControlHintManager.ControlHints

```

**C++**<br />
``` C++
public:
static property Dictionary<Control^, ControlHintInfo^>^ ControlHints {
	Dictionary<Control^, ControlHintInfo^>^ get ();
}
```

**F#**<br />
``` F#
static member ControlHints : Dictionary<Control, ControlHintInfo> with get

```


#### Property Value
Type: Dictionary(Control, <a href="T_DevCase_Core_Application_UserInterface_ControlHintInfo">ControlHintInfo</a>)<br />The control-hints that has been created.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlHintManager">ControlHintManager Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />