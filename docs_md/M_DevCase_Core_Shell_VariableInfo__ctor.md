# VariableInfo Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Shell_VariableInfo">VariableInfo</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public VariableInfo(
	EnvironmentVariableTarget scope,
	string name,
	string value
)
```

**VB**<br />
``` VB
Public Sub New ( 
	scope As EnvironmentVariableTarget,
	name As String,
	value As String
)
```

**VB Usage**<br />
``` VB Usage
Dim scope As EnvironmentVariableTarget
Dim name As String
Dim value As String

Dim instance As New VariableInfo(scope, name, 
	value)
```

**C++**<br />
``` C++
public:
VariableInfo(
	EnvironmentVariableTarget scope, 
	String^ name, 
	String^ value
)
```

**F#**<br />
``` F#
new : 
        scope : EnvironmentVariableTarget * 
        name : string * 
        value : string -> VariableInfo
```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: System.EnvironmentVariableTarget<br />The variable scope.</dd><dt>name</dt><dd>Type: System.String<br />The variable name.</dd><dt>value</dt><dd>Type: System.String<br />The variable value.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_VariableInfo">VariableInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />