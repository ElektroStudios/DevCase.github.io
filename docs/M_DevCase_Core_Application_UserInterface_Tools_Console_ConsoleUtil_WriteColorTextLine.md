# ConsoleUtil.WriteColorTextLine Method (String, Char[])
 

Writes colored text on the Console and adds an empty line at the end. 

 Use `*F##*` as the start delimiter of the ForeColor, use `*-F*` as the end delimiter of the ForeColor. 

 Use `*B##*` as the start delimiter of the BackColor, use `*-B*` as the end delimiter of the BackColor.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void WriteColorTextLine(
	string text,
	char[] delimiters
)
```

**VB**<br />
``` VB
Public Shared Sub WriteColorTextLine ( 
	text As String,
	delimiters As Char()
)
```

**VB Usage**<br />
``` VB Usage
Dim text As String
Dim delimiters As Char()

ConsoleUtil.WriteColorTextLine(text, delimiters)
```

**C++**<br />
``` C++
public:
static void WriteColorTextLine(
	String^ text, 
	array<wchar_t>^ delimiters
)
```

**F#**<br />
``` F#
static member WriteColorTextLine : 
        text : string * 
        delimiters : char[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>text</dt><dd>Type: System.String<br />The color-delimited text to write.</dd><dt>delimiters</dt><dd>Type: System.Char[]<br />A set of 1 or 2 delimiters to parse the color-delimited string.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
WriteColorTextLine("{B15}{F12} Hello World! {-F}{-B}", {"{"c, "}"c})
WriteColorTextLine(String.Format("*B15**F12* {0} *F0*{1} *-F**-B*", "Hello", "World!"), {"*"c})
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_WriteColorTextLine">WriteColorTextLine Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />