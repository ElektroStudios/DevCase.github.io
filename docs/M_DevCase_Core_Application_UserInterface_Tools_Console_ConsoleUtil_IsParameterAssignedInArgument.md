# ConsoleUtil.IsParameterAssignedInArgument Method (CommandLineParameter, String)
 

Determines whether the specified <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> is assigned in the given command-line argument.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsParameterAssignedInArgument(
	CommandLineParameter parameter,
	string argument
)
```

**VB**<br />
``` VB
Public Shared Function IsParameterAssignedInArgument ( 
	parameter As CommandLineParameter,
	argument As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim parameter As CommandLineParameter
Dim argument As String
Dim returnValue As Boolean

returnValue = ConsoleUtil.IsParameterAssignedInArgument(parameter, 
	argument)
```

**C++**<br />
``` C++
public:
static bool IsParameterAssignedInArgument(
	CommandLineParameter^ parameter, 
	String^ argument
)
```

**F#**<br />
``` F#
static member IsParameterAssignedInArgument : 
        parameter : CommandLineParameter * 
        argument : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>parameter</dt><dd>Type: <a href="T_DevCase_Core_Application_CommandLineParameter">DevCase.Core.Application.CommandLineParameter</a><br />The <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a>.</dd><dt>argument</dt><dd>Type: System.String<br />The command-line argument.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> is assigned in the given command-line argument; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_IsParameterAssignedInArgument">IsParameterAssignedInArgument Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />