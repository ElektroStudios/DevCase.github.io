# SetAclExitedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_SetAcl_Eventing_SetAclExitedEventArgs">SetAclExitedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SetAcl_Eventing">DevCase.ThirdParty.SetAcl.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SetAclExitedEventArgs(
	string arguments,
	string errorMessage,
	int exitCode
)
```

**VB**<br />
``` VB
Public Sub New ( 
	arguments As String,
	errorMessage As String,
	exitCode As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim arguments As String
Dim errorMessage As String
Dim exitCode As Integer

Dim instance As New SetAclExitedEventArgs(arguments, 
	errorMessage, exitCode)
```

**C++**<br />
``` C++
public:
SetAclExitedEventArgs(
	String^ arguments, 
	String^ errorMessage, 
	int exitCode
)
```

**F#**<br />
``` F#
new : 
        arguments : string * 
        errorMessage : string * 
        exitCode : int -> SetAclExitedEventArgs
```


#### Parameters
&nbsp;<dl><dt>arguments</dt><dd>Type: System.String<br />The arguments that was passed to the process.</dd><dt>errorMessage</dt><dd>Type: System.String<br />The arguments that was passed to the process.</dd><dt>exitCode</dt><dd>Type: System.Int32<br />The process exit code.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SetAcl_Eventing_SetAclExitedEventArgs">SetAclExitedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_SetAcl_Eventing">DevCase.ThirdParty.SetAcl.Eventing Namespace</a><br />