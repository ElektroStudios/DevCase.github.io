# ConsoleUtil.IsParameterAssignedInArgument(*T*) Method (CommandLineValueParameter(*T*), String)
 

Determines whether the specified <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> is assigned in the given command-line argument.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsParameterAssignedInArgument<T>(
	CommandLineValueParameter<T> parameter,
	string argument
)
where T : IConvertible

```

**VB**<br />
``` VB
Public Shared Function IsParameterAssignedInArgument(Of T As IConvertible) ( 
	parameter As CommandLineValueParameter(Of T),
	argument As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim parameter As CommandLineValueParameter(Of T)
Dim argument As String
Dim returnValue As Boolean

returnValue = ConsoleUtil.IsParameterAssignedInArgument(parameter, 
	argument)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : IConvertible
static bool IsParameterAssignedInArgument(
	CommandLineValueParameter<T>^ parameter, 
	String^ argument
)
```

**F#**<br />
``` F#
static member IsParameterAssignedInArgument : 
        parameter : CommandLineValueParameter<'T> * 
        argument : string -> bool  when 'T : IConvertible

```


#### Parameters
&nbsp;<dl><dt>parameter</dt><dd>Type: <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">DevCase.Core.Application.CommandLineValueParameter</a>(*T*)<br />The <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a>.</dd><dt>argument</dt><dd>Type: System.String<br />The command-line argument.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Application.UserInterface.Tools.Console.ConsoleUtil.IsParameterAssignedInArgument``1(DevCase.Core.Application.CommandLineValueParameter{``0},System.String)"\]</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified <a href="T_DevCase_Core_Application_CommandLineParameter">CommandLineParameter</a> is assigned in the given command-line argument; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil_IsParameterAssignedInArgument">IsParameterAssignedInArgument Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />