# HotkeyPressEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_Eventing_HotkeyPressEventArgs">HotkeyPressEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Eventing">DevCase.Core.Application.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public HotkeyPressEventArgs(
	Keys key,
	HotkeyModifiers modifiers,
	int id
)
```

**VB**<br />
``` VB
Public Sub New ( 
	key As Keys,
	modifiers As HotkeyModifiers,
	id As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim key As Keys
Dim modifiers As HotkeyModifiers
Dim id As Integer

Dim instance As New HotkeyPressEventArgs(key, modifiers, 
	id)
```

**C++**<br />
``` C++
public:
HotkeyPressEventArgs(
	Keys key, 
	HotkeyModifiers modifiers, 
	int id
)
```

**F#**<br />
``` F#
new : 
        key : Keys * 
        modifiers : HotkeyModifiers * 
        id : int -> HotkeyPressEventArgs
```


#### Parameters
&nbsp;<dl><dt>key</dt><dd>Type: System.Windows.Forms.Keys<br />The key assigned to the hotkey.</dd><dt>modifiers</dt><dd>Type: <a href="T_DevCase_Core_IO_HotkeyModifiers">DevCase.Core.IO.HotkeyModifiers</a><br />The key-modifiers assigned to the hotkey.</dd><dt>id</dt><dd>Type: System.Int32<br />The unique identifier assigned to the hotkey.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Eventing_HotkeyPressEventArgs">HotkeyPressEventArgs Class</a><br /><a href="N_DevCase_Core_Application_Eventing">DevCase.Core.Application.Eventing Namespace</a><br />