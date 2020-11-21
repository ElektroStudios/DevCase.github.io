# EnvironmentVariableUtil.GetValue Method 
 

Returns the value of the specified environment variable.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetValue(
	EnvironmentVariableTarget scope,
	string name
)
```

**VB**<br />
``` VB
Public Shared Function GetValue ( 
	scope As EnvironmentVariableTarget,
	name As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim scope As EnvironmentVariableTarget
Dim name As String
Dim returnValue As String

returnValue = EnvironmentVariableUtil.GetValue(scope, 
	name)
```

**C++**<br />
``` C++
public:
static String^ GetValue(
	EnvironmentVariableTarget scope, 
	String^ name
)
```

**F#**<br />
``` F#
static member GetValue : 
        scope : EnvironmentVariableTarget * 
        name : string -> string 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: System.EnvironmentVariableTarget<br />The environment scope that owns the variable.</dd><dt>name</dt><dd>Type: System.String<br />The variable name.</dd></dl>

#### Return Value
Type: String<br />The value of the specified environment variable.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>name</td></tr><tr><td>InvalidEnumArgumentException</td><td>scope</td></tr><tr><td>ArgumentException</td><td>The specified variable doesn't exists.;name</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
GetValue(EnvironmentVariableTarget.User, "System32", throwOnMissingVariable:=True)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_EnvironmentVariableUtil">EnvironmentVariableUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />