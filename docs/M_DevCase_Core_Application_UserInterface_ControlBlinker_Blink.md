# ControlBlinker.Blink Method 
 

Blinks the Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Blink(
	int interval = 500
)
```

**VB**<br />
``` VB
Public Overridable Sub Blink ( 
	Optional interval As Integer = 500
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlBlinker
Dim interval As Integer

instance.Blink(interval)
```

**C++**<br />
``` C++
public:
virtual void Blink(
	int interval = 500
)
```

**F#**<br />
``` F#
abstract Blink : 
        ?interval : int 
(* Defaults:
        let _interval = defaultArg interval 500
*)
-> unit 
override Blink : 
        ?interval : int 
(* Defaults:
        let _interval = defaultArg interval 500
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>interval (Optional)</dt><dd>Type: System.Int32<br />The blink interval, in ms.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlBlinker">ControlBlinker Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />