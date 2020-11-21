# ConsoleUtil.GetArgumentValue(*T*) Method 
 

Determines whether the specified <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> is assigned in the given command-line argument, then tries to get the assigned value of the parameter.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static T GetArgumentValue<T>(
	CommandLineValueParameter<T> parameter,
	string argument
)
where T : IConvertible

```

**VB**<br />
``` VB
Public Shared Function GetArgumentValue(Of T As IConvertible) ( 
	parameter As CommandLineValueParameter(Of T),
	argument As String
) As T
```

**VB Usage**<br />
``` VB Usage
Dim parameter As CommandLineValueParameter(Of T)
Dim argument As String
Dim returnValue As T

returnValue = ConsoleUtil.GetArgumentValue(parameter, 
	argument)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : IConvertible
static T GetArgumentValue(
	CommandLineValueParameter<T>^ parameter, 
	String^ argument
)
```

**F#**<br />
``` F#
static member GetArgumentValue : 
        parameter : CommandLineValueParameter<'T> * 
        argument : string -> 'T  when 'T : IConvertible

```


#### Parameters
&nbsp;<dl><dt>parameter</dt><dd>Type: <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">DevCase.Core.Application.CommandLineValueParameter</a>(*T*)<br />The <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a>.</dd><dt>argument</dt><dd>Type: System.String<br />The command-line argument.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Application.UserInterface.Tools.Console.ConsoleUtil.GetArgumentValue``1(DevCase.Core.Application.CommandLineValueParameter{``0},System.String)"\]</dd></dl>

#### Return Value
Type: *T*<br />The resulting value.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />