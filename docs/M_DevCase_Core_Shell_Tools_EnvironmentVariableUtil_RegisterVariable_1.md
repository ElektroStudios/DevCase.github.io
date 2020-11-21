# EnvironmentVariableUtil.RegisterVariable Method (EnvironmentVariableTarget, String, String, Boolean)
 

Registers a Windows environment variable.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RegisterVariable(
	EnvironmentVariableTarget scope,
	string name,
	string value,
	bool throwOnExistingVariable = false
)
```

**VB**<br />
``` VB
Public Shared Sub RegisterVariable ( 
	scope As EnvironmentVariableTarget,
	name As String,
	value As String,
	Optional throwOnExistingVariable As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim scope As EnvironmentVariableTarget
Dim name As String
Dim value As String
Dim throwOnExistingVariable As BooleanEnvironmentVariableUtil.RegisterVariable(scope, name, 
	value, throwOnExistingVariable)
```

**C++**<br />
``` C++
public:
static void RegisterVariable(
	EnvironmentVariableTarget scope, 
	String^ name, 
	String^ value, 
	bool throwOnExistingVariable = false
)
```

**F#**<br />
``` F#
static member RegisterVariable : 
        scope : EnvironmentVariableTarget * 
        name : string * 
        value : string * 
        ?throwOnExistingVariable : bool 
(* Defaults:
        let _throwOnExistingVariable = defaultArg throwOnExistingVariable false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: System.EnvironmentVariableTarget<br />The environment scope that will owns the variable.</dd><dt>name</dt><dd>Type: System.String<br />The variable name.</dd><dt>value</dt><dd>Type: System.String<br />The variable value.</dd><dt>throwOnExistingVariable (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), raises an exception if the variable already exists.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>name</td></tr><tr><td>InvalidEnumArgumentException</td><td>scope</td></tr><tr><td>ArgumentException</td><td>The specified variable already exists.;name</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
RegisterVariable(EnvironmentVariableTarget.tUser, "VariableName", "Elektro is the best!", throwOnExistingVariable:=True)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentVariableUtil">EnvironmentVariableUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_EnvironmentVariableUtil_RegisterVariable">RegisterVariable Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />