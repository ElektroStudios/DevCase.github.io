# EnvironmentVariableUtil.GetVariableInfo Method 
 

Finds an environment variable and returns a <a href="T_DevCase_Core_Shell_VariableInfo">VariableInfo</a> object that contains the variable data.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static VariableInfo GetVariableInfo(
	EnvironmentVariableTarget scope,
	string name
)
```

**VB**<br />
``` VB
Public Shared Function GetVariableInfo ( 
	scope As EnvironmentVariableTarget,
	name As String
) As VariableInfo
```

**VB Usage**<br />
``` VB Usage
Dim scope As EnvironmentVariableTarget
Dim name As String
Dim returnValue As VariableInfo

returnValue = EnvironmentVariableUtil.GetVariableInfo(scope, 
	name)
```

**C++**<br />
``` C++
public:
static VariableInfo^ GetVariableInfo(
	EnvironmentVariableTarget scope, 
	String^ name
)
```

**F#**<br />
``` F#
static member GetVariableInfo : 
        scope : EnvironmentVariableTarget * 
        name : string -> VariableInfo 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: System.EnvironmentVariableTarget<br />The environment scope that owns the variable.</dd><dt>name</dt><dd>Type: System.String<br />The variable name.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Shell_VariableInfo">VariableInfo</a><br />A <a href="T_DevCase_Core_Shell_VariableInfo">VariableInfo</a> object that contains the variable data.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>name</td></tr><tr><td>InvalidEnumArgumentException</td><td>scope</td></tr><tr><td>ArgumentException</td><td>The specified variable doesn't exists.;name</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentVariableUtil">EnvironmentVariableUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />