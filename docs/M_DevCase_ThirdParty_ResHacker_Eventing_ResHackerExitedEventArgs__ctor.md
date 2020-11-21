# ResHackerExitedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_ResHacker_Eventing_ResHackerExitedEventArgs">ResHackerExitedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ResHacker_Eventing">DevCase.ThirdParty.ResHacker.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ResHackerExitedEventArgs(
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

Dim instance As New ResHackerExitedEventArgs(arguments, 
	errorMessage, exitCode)
```

**C++**<br />
``` C++
public:
ResHackerExitedEventArgs(
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
        exitCode : int -> ResHackerExitedEventArgs
```


#### Parameters
&nbsp;<dl><dt>arguments</dt><dd>Type: System.String<br />The arguments that was passed to the process.</dd><dt>errorMessage</dt><dd>Type: System.String<br />The arguments that was passed to the process.</dd><dt>exitCode</dt><dd>Type: System.Int32<br />The process exit code.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ResHacker_Eventing_ResHackerExitedEventArgs">ResHackerExitedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_ResHacker_Eventing">DevCase.ThirdParty.ResHacker.Eventing Namespace</a><br />