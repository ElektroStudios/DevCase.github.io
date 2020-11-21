# ControlBlinker.BlinkText Method 
 

Blinks the text content of the Control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void BlinkText(
	int interval = 500,
	string customText = null
)
```

**VB**<br />
``` VB
Public Overridable Sub BlinkText ( 
	Optional interval As Integer = 500,
	Optional customText As String = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlBlinker
Dim interval As Integer
Dim customText As String

instance.BlinkText(interval, customText)
```

**C++**<br />
``` C++
public:
virtual void BlinkText(
	int interval = 500, 
	String^ customText = nullptr
)
```

**F#**<br />
``` F#
abstract BlinkText : 
        ?interval : int * 
        ?customText : string 
(* Defaults:
        let _interval = defaultArg interval 500
        let _customText = defaultArg customText null
*)
-> unit 
override BlinkText : 
        ?interval : int * 
        ?customText : string 
(* Defaults:
        let _interval = defaultArg interval 500
        let _customText = defaultArg customText null
*)
-> unit 
```


#### Parameters
&nbsp;<dl><dt>interval (Optional)</dt><dd>Type: System.Int32<br />The blink interval.</dd><dt>customText (Optional)</dt><dd>Type: System.String<br />A custom text to blink.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlBlinker">ControlBlinker Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />