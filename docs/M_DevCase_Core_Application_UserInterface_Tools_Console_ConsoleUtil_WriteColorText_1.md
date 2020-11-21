# ConsoleUtil.WriteColorText Method (String, ConsoleColor, ConsoleColor)
 

Writes colored text on the Console.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void WriteColorText(
	string text,
	ConsoleColor foreColor,
	ConsoleColor backColor
)
```

**VB**<br />
``` VB
Public Shared Sub WriteColorText ( 
	text As String,
	foreColor As ConsoleColor,
	backColor As ConsoleColor
)
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim foreColor As ConsoleColor
Dim backColor As ConsoleColorConsoleUtil.WriteColorText(text, foreColor, 
	backColor)
```

**C++**<br />
``` C++
public:
static void WriteColorText(
	String^ text, 
	ConsoleColor foreColor, 
	ConsoleColor backColor
)
```

**F#**<br />
``` F#
static member WriteColorText : 
        text : string * 
        foreColor : ConsoleColor * 
        backColor : ConsoleColor -> unit 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The text to write.</dd><dt>foreColor</dt><dd>Type: System.ConsoleColor<br />The text color.</dd><dt>backColor</dt><dd>Type: System.ConsoleColor<br />The background color.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
WriteColorText(" Hello World! ", ConsoleColor.Blue, ConsoleColor.Blue)
WriteColorText(" Hello World! ", ConsoleColor.Blue, Nothing)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_WriteColorText">WriteColorText Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />