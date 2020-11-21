# Hotkey Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_Hotkey">Hotkey</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Hotkey(
	HotkeyModifiers modifier,
	Keys key
)
```

**VB**<br />
``` VB
Public Sub New ( 
	modifier As HotkeyModifiers,
	key As Keys
)
```

**VB Usage**<br />
``` VB Usage
Dim modifier As HotkeyModifiers
Dim key As Keys

Dim instance As New Hotkey(modifier, 
	key)
```

**C++**<br />
``` C++
public:
Hotkey(
	HotkeyModifiers modifier, 
	Keys key
)
```

**F#**<br />
``` F#
new : 
        modifier : HotkeyModifiers * 
        key : Keys -> Hotkey
```


#### Parameters
&nbsp;<dl><dt>modifier</dt><dd>Type: <a href="T_DevCase_Core_IO_HotkeyModifiers">DevCase.Core.IO.HotkeyModifiers</a><br />One or more key-modifiers to assign to the hotkey.</dd><dt>key</dt><dd>Type: System.Windows.Forms.Keys<br />The key to assign to the hotkey.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="T_DevCase_Core_Application_Exceptions_HotkeyIsRegisteredException">HotkeyIsRegisteredException</a></td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Hotkey">Hotkey Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />