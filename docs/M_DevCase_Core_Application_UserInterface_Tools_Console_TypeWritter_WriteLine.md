# TypeWritter.WriteLine Method 
 

Writes text simulating a typewritter effect, and adds a break-line at the end.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void WriteLine(
	string text,
	int typeSpeed = 75,
	int pauseDuration = 400
)
```

**VB**<br />
``` VB
Public Shared Sub WriteLine ( 
	text As String,
	Optional typeSpeed As Integer = 75,
	Optional pauseDuration As Integer = 400
)
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim typeSpeed As Integer
Dim pauseDuration As Integer

TypeWritter.WriteLine(text, typeSpeed, pauseDuration)
```

**C++**<br />
``` C++
public:
static void WriteLine(
	String^ text, 
	int typeSpeed = 75, 
	int pauseDuration = 400
)
```

**F#**<br />
``` F#
static member WriteLine : 
        text : string * 
        ?typeSpeed : int * 
        ?pauseDuration : int 
(* Defaults:
        let _typeSpeed = defaultArg typeSpeed 75
        let _pauseDuration = defaultArg pauseDuration 400
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text to type.</dd><dt>typeSpeed (Optional)</dt><dd>Type: System.Int32<br />The typying speed, in ms.</dd><dt>pauseDuration (Optional)</dt><dd>Type: System.Int32<br />The pause duration of the punctuation characters, in ms.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter">TypeWritter Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />