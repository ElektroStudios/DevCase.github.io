# ConsoleUtil.CommandLineParameterSuffixToChar Method 
 

Translates a <a href="T_DevCase_Core_Application_CommandLineParameterSuffix">CommandLineParameterSuffix</a> to its equivalent character. 

 For Example: CommandLineParameterSuffix.EqualsSign -> "="

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static char CommandLineParameterSuffixToChar(
	CommandLineParameterSuffix suffix
)
```

**VB**<br />
``` VB
Public Shared Function CommandLineParameterSuffixToChar ( 
	suffix As CommandLineParameterSuffix
) As Char
```

**VB Usage**<br />
``` VB Usage
Dim suffix As CommandLineParameterSuffix
Dim returnValue As Char

returnValue = ConsoleUtil.CommandLineParameterSuffixToChar(suffix)
```

**C++**<br />
``` C++
public:
static wchar_t CommandLineParameterSuffixToChar(
	CommandLineParameterSuffix suffix
)
```

**F#**<br />
``` F#
static member CommandLineParameterSuffixToChar : 
        suffix : CommandLineParameterSuffix -> char 

```


#### Parameters
&nbsp;<dl><dt>suffix</dt><dd>Type: <a href="T_DevCase_Core_Application_CommandLineParameterSuffix">DevCase.Core.Application.CommandLineParameterSuffix</a><br />\[Missing <param name="suffix"/> documentation for "M:DevCase.Core.Application.UserInterface.Tools.Console.ConsoleUtil.CommandLineParameterSuffixToChar(DevCase.Core.Application.CommandLineParameterSuffix)"\]</dd></dl>

#### Return Value
Type: Char<br />The resulting suffix character.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />