# EnvironmentVariableUtil.UnregisterVariable Method (VariableInfo, Boolean)
 

Unregisters a Windows environment variable.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void UnregisterVariable(
	VariableInfo variableInfo,
	bool throwOnMissingVariable = false
)
```

**VB**<br />
``` VB
Public Shared Sub UnregisterVariable ( 
	variableInfo As VariableInfo,
	Optional throwOnMissingVariable As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim variableInfo As VariableInfo
Dim throwOnMissingVariable As BooleanEnvironmentVariableUtil.UnregisterVariable(variableInfo, 
	throwOnMissingVariable)
```

**C++**<br />
``` C++
public:
static void UnregisterVariable(
	VariableInfo^ variableInfo, 
	bool throwOnMissingVariable = false
)
```

**F#**<br />
``` F#
static member UnregisterVariable : 
        variableInfo : VariableInfo * 
        ?throwOnMissingVariable : bool 
(* Defaults:
        let _throwOnMissingVariable = defaultArg throwOnMissingVariable false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>variableInfo</dt><dd>Type: <a href="T_DevCase_Core_Shell_VariableInfo">DevCase.Core.Shell.VariableInfo</a><br />A <a href="T_DevCase_Core_Shell_VariableInfo">VariableInfo</a> object that contains the variable data.</dd><dt>throwOnMissingVariable (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), raises an exception if the variable doesn't exists.</dd></dl>

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