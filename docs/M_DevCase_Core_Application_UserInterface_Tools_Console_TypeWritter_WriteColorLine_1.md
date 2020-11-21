# TypeWritter.WriteColorLine Method (String, ConsoleColor, ConsoleColor, Int32, Int32)
 

Writes colored-text simulating a typewritter effect, and adds an empty line at the end.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void WriteColorLine(
	string text,
	ConsoleColor foreColor,
	ConsoleColor backColor,
	int typeSpeed = 75,
	int pauseDuration = 400
)
```

**VB**<br />
``` VB
Public Shared Sub WriteColorLine ( 
	text As String,
	foreColor As ConsoleColor,
	backColor As ConsoleColor,
	Optional typeSpeed As Integer = 75,
	Optional pauseDuration As Integer = 400
)
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim foreColor As ConsoleColor
Dim backColor As ConsoleColor
Dim typeSpeed As Integer
Dim pauseDuration As Integer

TypeWritter.WriteColorLine(text, foreColor, 
	backColor, typeSpeed, pauseDuration)
```

**C++**<br />
``` C++
public:
static void WriteColorLine(
	String^ text, 
	ConsoleColor foreColor, 
	ConsoleColor backColor, 
	int typeSpeed = 75, 
	int pauseDuration = 400
)
```

**F#**<br />
``` F#
static member WriteColorLine : 
        text : string * 
        foreColor : ConsoleColor * 
        backColor : ConsoleColor * 
        ?typeSpeed : int * 
        ?pauseDuration : int 
(* Defaults:
        let _typeSpeed = defaultArg typeSpeed 75
        let _pauseDuration = defaultArg pauseDuration 400
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text to write.</dd><dt>foreColor</dt><dd>Type: System.ConsoleColor<br />The text color.</dd><dt>backColor</dt><dd>Type: System.ConsoleColor<br />The background color.</dd><dt>typeSpeed (Optional)</dt><dd>Type: System.Int32<br />The typying speed, in ms.</dd><dt>pauseDuration (Optional)</dt><dd>Type: System.Int32<br />The pause duration of the punctuation characters, in ms.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
WriteColorLine(" Hello World! ", ConsoleColor.Magenta, ConsoleColor.Gray)
WriteColorLine(" Hello World! ", ConsoleColor.Magenta, Nothing)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter">TypeWritter Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter_WriteColorLine">WriteColorLine Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />