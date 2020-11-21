# ConsoleUtil.IsParameterAssignedInArgument Method (CommandLineParameterPrefix, String, String)
 

Determines whether the specified command-line parameter is assigned in the given command-line argument.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsParameterAssignedInArgument(
	CommandLineParameterPrefix prefix,
	string parameterName,
	string argument
)
```

**VB**<br />
``` VB
Public Shared Function IsParameterAssignedInArgument ( 
	prefix As CommandLineParameterPrefix,
	parameterName As String,
	argument As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim prefix As CommandLineParameterPrefix
Dim parameterName As String
Dim argument As String
Dim returnValue As Boolean

returnValue = ConsoleUtil.IsParameterAssignedInArgument(prefix, 
	parameterName, argument)
```

**C++**<br />
``` C++
public:
static bool IsParameterAssignedInArgument(
	CommandLineParameterPrefix prefix, 
	String^ parameterName, 
	String^ argument
)
```

**F#**<br />
``` F#
static member IsParameterAssignedInArgument : 
        prefix : CommandLineParameterPrefix * 
        parameterName : string * 
        argument : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>prefix</dt><dd>Type: <a href="T_DevCase_Core_Application_CommandLineParameterPrefix">DevCase.Core.Application.CommandLineParameterPrefix</a><br />The prefix of the command-line parameter's name.</dd><dt>parameterName</dt><dd>Type: System.String<br />The name of the command-line parameter.</dd><dt>argument</dt><dd>Type: System.String<br />The command-line argument.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified command-line parameter is assigned in the given command-line argument; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_IsParameterAssignedInArgument">IsParameterAssignedInArgument Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />