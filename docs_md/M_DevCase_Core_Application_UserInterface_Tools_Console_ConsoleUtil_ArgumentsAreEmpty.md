# ConsoleUtil.ArgumentsAreEmpty Method 
 

Determines whether the command-line arguments for the current process are empty.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ArgumentsAreEmpty(
	IEnumerable<string> args = null
)
```

**VB**<br />
``` VB
Public Shared Function ArgumentsAreEmpty ( 
	Optional args As IEnumerable(Of String) = Nothing
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim args As IEnumerable(Of String)
Dim returnValue As Boolean

returnValue = ConsoleUtil.ArgumentsAreEmpty(args)
```

**C++**<br />
``` C++
public:
static bool ArgumentsAreEmpty(
	IEnumerable<String^>^ args = nullptr
)
```

**F#**<br />
``` F#
static member ArgumentsAreEmpty : 
        ?args : IEnumerable<string> 
(* Defaults:
        let _args = defaultArg args null
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>args (Optional)</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />A custom collection of arguments to examine.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the arguments are empty, otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />