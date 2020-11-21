# ControlBlinker.UnblinkText Method 
 

Stop blinking the text content of the Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void UnblinkText(
	bool restoreText = false
)
```

**VB**<br />
``` VB
Public Overridable Sub UnblinkText ( 
	Optional restoreText As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlBlinker
Dim restoreText As Boolean

instance.UnblinkText(restoreText)
```

**C++**<br />
``` C++
public:
virtual void UnblinkText(
	bool restoreText = false
)
```

**F#**<br />
``` F#
abstract UnblinkText : 
        ?restoreText : bool 
(* Defaults:
        let _restoreText = defaultArg restoreText false
*)
-> unit 
override UnblinkText : 
        ?restoreText : bool 
(* Defaults:
        let _restoreText = defaultArg restoreText false
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>restoreText (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), the control text is resetted to the initial state before started blinking.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlBlinker">ControlBlinker Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />