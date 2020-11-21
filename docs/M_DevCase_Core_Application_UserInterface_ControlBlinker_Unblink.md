# ControlBlinker.Unblink Method 
 

Stop blinking the Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Unblink(
	bool visible = true
)
```

**VB**<br />
``` VB
Public Overridable Sub Unblink ( 
	Optional visible As Boolean = true
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlBlinker
Dim visible As Boolean

instance.Unblink(visible)
```

**C++**<br />
``` C++
public:
virtual void Unblink(
	bool visible = true
)
```

**F#**<br />
``` F#
abstract Unblink : 
        ?visible : bool 
(* Defaults:
        let _visible = defaultArg visible true
*)
-> unit 
override Unblink : 
        ?visible : bool 
(* Defaults:
        let _visible = defaultArg visible true
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>visible (Optional)</dt><dd>Type: System.Boolean<br />The visibility of the control.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlBlinker">ControlBlinker Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />