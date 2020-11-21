# MP3GainExitedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs">MP3GainExitedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Gain_Eventing">DevCase.ThirdParty.MP3Gain.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MP3GainExitedEventArgs(
	string arguments,
	string file,
	MP3GainOperation operation,
	string infoMessage,
	string errorMessage,
	int gainLevel,
	int exitCode
)
```

**VB**<br />
``` VB
Public Sub New ( 
	arguments As String,
	file As String,
	operation As MP3GainOperation,
	infoMessage As String,
	errorMessage As String,
	gainLevel As Integer,
	exitCode As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim arguments As String
Dim file As String
Dim operation As MP3GainOperation
Dim infoMessage As String
Dim errorMessage As String
Dim gainLevel As Integer
Dim exitCode As Integer

Dim instance As New MP3GainExitedEventArgs(arguments, 
	file, operation, infoMessage, errorMessage, 
	gainLevel, exitCode)
```

**C++**<br />
``` C++
public:
MP3GainExitedEventArgs(
	String^ arguments, 
	String^ file, 
	MP3GainOperation operation, 
	String^ infoMessage, 
	String^ errorMessage, 
	int gainLevel, 
	int exitCode
)
```

**F#**<br />
``` F#
new : 
        arguments : string * 
        file : string * 
        operation : MP3GainOperation * 
        infoMessage : string * 
        errorMessage : string * 
        gainLevel : int * 
        exitCode : int -> MP3GainExitedEventArgs
```


#### Parameters
&nbsp;<dl><dt>arguments</dt><dd>Type: System.String<br />The arguments that was passed to the process.</dd><dt>file</dt><dd>Type: System.String<br />The source audio filepath that was passed to the process.</dd><dt>operation</dt><dd>Type: <a href="T_DevCase_ThirdParty_MP3Gain_MP3GainOperation">DevCase.ThirdParty.MP3Gain.MP3GainOperation</a><br />The MP3Gain operation that is being realized.</dd><dt>infoMessage</dt><dd>Type: System.String<br />The information message of the realized task.</dd><dt>errorMessage</dt><dd>Type: System.String<br />The error messages (if any).</dd><dt>gainLevel</dt><dd>Type: System.Int32<br />The volume gain level change applied to file, in decibels. 

 This value is always `0` if performing a <a href="T_DevCase_ThirdParty_MP3Gain_MP3GainOperation">CheckTagInfo</a> task.</dd><dt>exitCode</dt><dd>Type: System.Int32<br />The process exit code.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs">MP3GainExitedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_MP3Gain_Eventing">DevCase.ThirdParty.MP3Gain.Eventing Namespace</a><br />