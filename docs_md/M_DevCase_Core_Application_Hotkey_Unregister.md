# Hotkey.Unregister Method 
 

Unregisters this hotkey from the system. So after calling this method the hotkey turns unavailable. 

 Note that the hotkey can be re-registered at any time calling the <a href="M_DevCase_Core_Application_Hotkey_Register">Register()</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Unregister(
	bool resetCounter = false
)
```

**VB**<br />
``` VB
Public Overridable Sub Unregister ( 
	Optional resetCounter As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Hotkey
Dim resetCounter As Boolean

instance.Unregister(resetCounter)
```

**C++**<br />
``` C++
public:
virtual void Unregister(
	bool resetCounter = false
)
```

**F#**<br />
``` F#
abstract Unregister : 
        ?resetCounter : bool 
(* Defaults:
        let _resetCounter = defaultArg resetCounter false
*)
-> unit 
override Unregister : 
        ?resetCounter : bool 
(* Defaults:
        let _resetCounter = defaultArg resetCounter false
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>resetCounter (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), resets the <a href="P_DevCase_Core_Application_Hotkey_Count">Count</a> property that keeps track of the amount of times that the hotkey was pressed.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td><a href="T_DevCase_Core_Application_Exceptions_HotkeyIsNotRegisteredException">HotkeyIsNotRegisteredException</a></td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Hotkey">Hotkey Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />