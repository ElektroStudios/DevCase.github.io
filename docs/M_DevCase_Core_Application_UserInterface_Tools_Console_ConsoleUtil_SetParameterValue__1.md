# ConsoleUtil.SetParameterValue(*T*) Method 
 

Determines whether the specified <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> is assigned in the given command-line argument, then tries to set the assigned value of the parameter.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SetParameterValue<T>(
	ref CommandLineValueParameter<T> refParameter,
	string argument
)
where T : IConvertible

```

**VB**<br />
``` VB
Public Shared Sub SetParameterValue(Of T As IConvertible) ( 
	ByRef refParameter As CommandLineValueParameter(Of T),
	argument As String
)
```

**VB Usage**<br />
``` VB Usage
Dim refParameter As CommandLineValueParameter(Of T)
Dim argument As StringConsoleUtil.SetParameterValue(refParameter, 
	argument)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : IConvertible
static void SetParameterValue(
	CommandLineValueParameter<T>^% refParameter, 
	String^ argument
)
```

**F#**<br />
``` F#
static member SetParameterValue : 
        refParameter : CommandLineValueParameter<'T> byref * 
        argument : string -> unit  when 'T : IConvertible

```


#### Parameters
&nbsp;<dl><dt>refParameter</dt><dd>Type: <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">DevCase.Core.Application.CommandLineValueParameter</a>(*T*)<br />The <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a>.</dd><dt>argument</dt><dd>Type: System.String<br />The command-line argument.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Application.UserInterface.Tools.Console.ConsoleUtil.SetParameterValue``1(DevCase.Core.Application.CommandLineValueParameter{``0}@,System.String)"\]</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />