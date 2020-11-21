# MP3GainStartedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainStartedEventArgs">MP3GainStartedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Gain_Eventing">DevCase.ThirdParty.MP3Gain.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MP3GainStartedEventArgs(
	string arguments,
	string file,
	MP3GainOperation operation
)
```

**VB**<br />
``` VB
Public Sub New ( 
	arguments As String,
	file As String,
	operation As MP3GainOperation
)
```

**VB Usage**<br />
``` VB Usage
Dim arguments As String
Dim file As String
Dim operation As MP3GainOperation

Dim instance As New MP3GainStartedEventArgs(arguments, 
	file, operation)
```

**C++**<br />
``` C++
public:
MP3GainStartedEventArgs(
	String^ arguments, 
	String^ file, 
	MP3GainOperation operation
)
```

**F#**<br />
``` F#
new : 
        arguments : string * 
        file : string * 
        operation : MP3GainOperation -> MP3GainStartedEventArgs
```


#### Parameters
&nbsp;<dl><dt>arguments</dt><dd>Type: System.String<br />The arguments that was passed to the process.</dd><dt>file</dt><dd>Type: System.String<br />The source audio filepath that was passed to the process.</dd><dt>operation</dt><dd>Type: <a href="T_DevCase_ThirdParty_MP3Gain_MP3GainOperation">DevCase.ThirdParty.MP3Gain.MP3GainOperation</a><br />The MP3Gain operation that is being realized.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainStartedEventArgs">MP3GainStartedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_MP3Gain_Eventing">DevCase.ThirdParty.MP3Gain.Eventing Namespace</a><br />