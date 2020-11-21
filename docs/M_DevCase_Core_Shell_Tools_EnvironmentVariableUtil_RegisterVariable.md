# EnvironmentVariableUtil.RegisterVariable Method (VariableInfo, Boolean)
 

Registers a Windows environment variable.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RegisterVariable(
	VariableInfo variableInfo,
	bool throwOnExistingVariable = false
)
```

**VB**<br />
``` VB
Public Shared Sub RegisterVariable ( 
	variableInfo As VariableInfo,
	Optional throwOnExistingVariable As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim variableInfo As VariableInfo
Dim throwOnExistingVariable As BooleanEnvironmentVariableUtil.RegisterVariable(variableInfo, 
	throwOnExistingVariable)
```

**C++**<br />
``` C++
public:
static void RegisterVariable(
	VariableInfo^ variableInfo, 
	bool throwOnExistingVariable = false
)
```

**F#**<br />
``` F#
static member RegisterVariable : 
        variableInfo : VariableInfo * 
        ?throwOnExistingVariable : bool 
(* Defaults:
        let _throwOnExistingVariable = defaultArg throwOnExistingVariable false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>variableInfo</dt><dd>Type: <a href="T_DevCase_Core_Shell_VariableInfo">DevCase.Core.Shell.VariableInfo</a><br />A <a href="T_DevCase_Core_Shell_VariableInfo">VariableInfo</a> object that contains the variable data.</dd><dt>throwOnExistingVariable (Optional)</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), raises an exception if the variable already exists.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
RegisterVariable(
    New VariableInfo(EnvironmentVariableTarget.User, "VariableName", "Elektro is the best!"),
                     throwOnExistingVariable:=True)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentVariableUtil">EnvironmentVariableUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_EnvironmentVariableUtil_RegisterVariable">RegisterVariable Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />