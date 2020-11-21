# ConsoleUtil.WriteColorTextLine Method (String, ConsoleColor, ConsoleColor)
 

Writes colored text on the Console and adds an empty line at the end.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void WriteColorTextLine(
	string text,
	ConsoleColor foreColor,
	ConsoleColor backColor
)
```

**VB**<br />
``` VB
Public Shared Sub WriteColorTextLine ( 
	text As String,
	foreColor As ConsoleColor,
	backColor As ConsoleColor
)
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim foreColor As ConsoleColor
Dim backColor As ConsoleColorConsoleUtil.WriteColorTextLine(text, foreColor, 
	backColor)
```

**C++**<br />
``` C++
public:
static void WriteColorTextLine(
	String^ text, 
	ConsoleColor foreColor, 
	ConsoleColor backColor
)
```

**F#**<br />
``` F#
static member WriteColorTextLine : 
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
WriteColorTextLine(" Hello World! ", ConsoleColor.Magenta, ConsoleColor.Gray)
WriteColorTextLine(" Hello World! ", ConsoleColor.Magenta, Nothing)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_WriteColorTextLine">WriteColorTextLine Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />