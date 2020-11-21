# TypeWritter.WriteEmptyLine Method 
 

Writes an empty line.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void WriteEmptyLine(
	int pauseDuration = 750
)
```

**VB**<br />
``` VB
Public Shared Sub WriteEmptyLine ( 
	Optional pauseDuration As Integer = 750
)
```

**VB Usage**<br />
``` VB Usage
Dim pauseDuration As Integer

TypeWritter.WriteEmptyLine(pauseDuration)
```

**C++**<br />
``` C++
public:
static void WriteEmptyLine(
	int pauseDuration = 750
)
```

**F#**<br />
``` F#
static member WriteEmptyLine : 
        ?pauseDuration : int 
(* Defaults:
        let _pauseDuration = defaultArg pauseDuration 750
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>pauseDuration (Optional)</dt><dd>Type: System.Int32<br />The pause duration of the empty line, in ms.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_TypeWritter">TypeWritter Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />