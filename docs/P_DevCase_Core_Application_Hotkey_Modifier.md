# Hotkey.Modifier Property 
 

Gets the key-modifiers assigned to the hotkey.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual HotkeyModifiers Modifier { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Modifier As HotkeyModifiers
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As Hotkey
Dim value As HotkeyModifiers

value = instance.Modifier

```

**C++**<br />
``` C++
public:
virtual property HotkeyModifiers Modifier {
	HotkeyModifiers get ();
}
```

**F#**<br />
``` F#
abstract Modifier : HotkeyModifiers with get
override Modifier : HotkeyModifiers with get
```


#### Property Value
Type: <a href="T_DevCase_Core_IO_HotkeyModifiers">HotkeyModifiers</a><br />The key-modifiers assigned to the hotkey.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Hotkey">Hotkey Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />