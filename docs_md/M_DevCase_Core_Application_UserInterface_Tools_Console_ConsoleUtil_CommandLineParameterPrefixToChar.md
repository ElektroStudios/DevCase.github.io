# ConsoleUtil.CommandLineParameterPrefixToChar Method 
 

Translates a <a href="T_DevCase_Core_Application_CommandLineParameterPrefix">CommandLineParameterPrefix</a> to its equivalent character. 

 For Example: CommandLineParameterPrefix.Slash -> "/"

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static char CommandLineParameterPrefixToChar(
	CommandLineParameterPrefix prefix
)
```

**VB**<br />
``` VB
Public Shared Function CommandLineParameterPrefixToChar ( 
	prefix As CommandLineParameterPrefix
) As Char
```

**VB Usage**<br />
``` VB Usage
Dim prefix As CommandLineParameterPrefix
Dim returnValue As Char

returnValue = ConsoleUtil.CommandLineParameterPrefixToChar(prefix)
```

**C++**<br />
``` C++
public:
static wchar_t CommandLineParameterPrefixToChar(
	CommandLineParameterPrefix prefix
)
```

**F#**<br />
``` F#
static member CommandLineParameterPrefixToChar : 
        prefix : CommandLineParameterPrefix -> char 

```


#### Parameters
&nbsp;<dl><dt>prefix</dt><dd>Type: <a href="T_DevCase_Core_Application_CommandLineParameterPrefix">DevCase.Core.Application.CommandLineParameterPrefix</a><br />\[Missing <param name="prefix"/> documentation for "M:DevCase.Core.Application.UserInterface.Tools.Console.ConsoleUtil.CommandLineParameterPrefixToChar(DevCase.Core.Application.CommandLineParameterPrefix)"\]</dd></dl>

#### Return Value
Type: Char<br />The resulting prefix character.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />