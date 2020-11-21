# TypeWritter.WriteColor Method (String, Char[], Int32, Int32)
 

Writes colored text simulating a typewritter effect. 

 Use `*F##*` as the start delimiter of the ForeColor, use `*-F*` as the end delimiter of the ForeColor. 

 Use `*B##*` as the start delimiter of the BackColor, use `*-B*` as the end delimiter of the BackColor.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void WriteColor(
	string text,
	char[] delimiters,
	int typeSpeed = 75,
	int pauseDuration = 400
)
```

**VB**<br />
``` VB
Public Shared Sub WriteColor ( 
	text As String,
	delimiters As Char(),
	Optional typeSpeed As Integer = 75,
	Optional pauseDuration As Integer = 400
)
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim delimiters As Char()
Dim typeSpeed As Integer
Dim pauseDuration As Integer

TypeWritter.WriteColor(text, delimiters, 
	typeSpeed, pauseDuration)
```

**C++**<br />
``` C++
public:
static void WriteColor(
	String^ text, 
	array<wchar_t>^ delimiters, 
	int typeSpeed = 75, 
	int pauseDuration = 400
)
```

**F#**<br />
``` F#
static member WriteColor : 
        text : string * 
        delimiters : char[] * 
        ?typeSpeed : int * 
        ?pauseDuration : int 
(* Defaults:
        let _typeSpeed = defaultArg typeSpeed 75
        let _pauseDuration = defaultArg pauseDuration 400
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The color-delimited text to write.</dd><dt>delimiters</dt><dd>Type: System.Char[]<br />A set of 1 or 2 delimiters to parse the color-delimited string.</dd><dt>typeSpeed (Optional)</dt><dd>Type: System.Int32<br />The typying speed, in ms.</dd><dt>pauseDuration (Optional)</dt><dd>Type: System.Int32<br />The pause duration of the punctuation characters, in ms.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
WriteColor("*F10*Hello *F14*World!*-F*", {"*"c})
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter">TypeWritter Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteColor">WriteColor Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />