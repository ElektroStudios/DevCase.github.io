# TypeWritter.Write Method 
 

Writes text simulating a typewritter effect.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Write(
	string text,
	int typeSpeed,
	int pauseDuration
)
```

**VB**<br />
``` VB
Public Shared Sub Write ( 
	text As String,
	typeSpeed As Integer,
	pauseDuration As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim typeSpeed As Integer
Dim pauseDuration As Integer

TypeWritter.Write(text, typeSpeed, pauseDuration)
```

**C++**<br />
``` C++
public:
static void Write(
	String^ text, 
	int typeSpeed, 
	int pauseDuration
)
```

**F#**<br />
``` F#
static member Write : 
        text : string * 
        typeSpeed : int * 
        pauseDuration : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text to type.</dd><dt>typeSpeed</dt><dd>Type: System.Int32<br />The typying speed, in ms.</dd><dt>pauseDuration</dt><dd>Type: System.Int32<br />The pause duration of the punctuation characters, in ms.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter">TypeWritter Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />