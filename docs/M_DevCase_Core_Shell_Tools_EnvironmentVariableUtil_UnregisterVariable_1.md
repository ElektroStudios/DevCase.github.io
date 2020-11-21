# EnvironmentVariableUtil.UnregisterVariable Method (EnvironmentVariableTarget, String, Boolean)
 

Unregisters a Windows environment variable.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void UnregisterVariable(
	EnvironmentVariableTarget scope,
	string name,
	bool throwOnMissingVariable = false
)
```

**VB**<br />
``` VB
Public Shared Sub UnregisterVariable ( 
	scope As EnvironmentVariableTarget,
	name As String,
	Optional throwOnMissingVariable As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim scope As EnvironmentVariableTarget
Dim name As String
Dim throwOnMissingVariable As BooleanEnvironmentVariableUtil.UnregisterVariable(scope, name, 
	throwOnMissingVariable)
```

**C++**<br />
``` C++
public:
static void UnregisterVariable(
	EnvironmentVariableTarget scope, 
	String^ name, 
	bool throwOnMissingVariable = false
)
```

**F#**<br />
``` F#
static member UnregisterVariable : 
        scope : EnvironmentVariableTarget * 
        name : string * 
        ?throwOnMissingVariable : bool 
(* Defaults:
        let _throwOnMissingVariable = defaultArg throwOnMissingVariable false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: System.EnvironmentVariableTarget<br />The environment scope that owns the variable.</dd><dt>name</dt><dd>Type: System.String<br />The variable name.</dd><dt>throwOnMissingVariable (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), raises an exception if the variable doesn't exists.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>name</td></tr><tr><td>InvalidEnumArgumentException</td><td>scope</td></tr><tr><td>ArgumentException</td><td>The specified variable doesn't exists.;name</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
UnregisterVariable(EnvironmentVariableTarget.User, "VariableName", throwOnMissingVariable:=True)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentVariableUtil">EnvironmentVariableUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_EnvironmentVariableUtil_UnregisterVariable">UnregisterVariable Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />