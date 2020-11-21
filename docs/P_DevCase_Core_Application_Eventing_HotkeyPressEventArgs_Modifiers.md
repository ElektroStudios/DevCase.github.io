# HotkeyPressEventArgs.Modifiers Property 
 

Gets the key-modifiers assigned to the hotkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Eventing">DevCase.Core.Application.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public HotkeyModifiers Modifiers { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Modifiers As HotkeyModifiers
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As HotkeyPressEventArgs
Dim value As HotkeyModifiers

value = instance.Modifiers

```

**C++**<br />
``` C++
public:
property HotkeyModifiers Modifiers {
	HotkeyModifiers get ();
}
```

**F#**<br />
``` F#
member Modifiers : HotkeyModifiers with get

```


#### Property Value
Type: <a href="T_DevCase_Core_IO_HotkeyModifiers">HotkeyModifiers</a><br />The key-modifiers assigned to the hotkey.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Eventing_HotkeyPressEventArgs">HotkeyPressEventArgs Class</a><br /><a href="N_DevCase_Core_Application_Eventing">DevCase.Core.Application.Eventing Namespace</a><br />