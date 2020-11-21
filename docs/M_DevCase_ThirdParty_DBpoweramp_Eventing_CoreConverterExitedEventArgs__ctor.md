# CoreConverterExitedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterExitedEventArgs">CoreConverterExitedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DBpoweramp_Eventing">DevCase.ThirdParty.DBpoweramp.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CoreConverterExitedEventArgs(
	string inputFile,
	string outputFile,
	CoreConverterTask task,
	string errorMessage,
	string elapsedTime,
	int exitCode
)
```

**VB**<br />
``` VB
Public Sub New ( 
	inputFile As String,
	outputFile As String,
	task As CoreConverterTask,
	errorMessage As String,
	elapsedTime As String,
	exitCode As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim inputFile As String
Dim outputFile As String
Dim task As CoreConverterTask
Dim errorMessage As String
Dim elapsedTime As String
Dim exitCode As Integer

Dim instance As New CoreConverterExitedEventArgs(inputFile, 
	outputFile, task, errorMessage, elapsedTime, 
	exitCode)
```

**C++**<br />
``` C++
public:
CoreConverterExitedEventArgs(
	String^ inputFile, 
	String^ outputFile, 
	CoreConverterTask task, 
	String^ errorMessage, 
	String^ elapsedTime, 
	int exitCode
)
```

**F#**<br />
``` F#
new : 
        inputFile : string * 
        outputFile : string * 
        task : CoreConverterTask * 
        errorMessage : string * 
        elapsedTime : string * 
        exitCode : int -> CoreConverterExitedEventArgs
```


#### Parameters
&nbsp;<dl><dt>inputFile</dt><dd>Type: System.String<br />The filepath that was passed as argument to the process.</dd><dt>outputFile</dt><dd>Type: System.String<br />The filepath of the file being converted.</dd><dt>task</dt><dd>Type: <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterTask">DevCase.ThirdParty.DBpoweramp.CoreConverterTask</a><br />The <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterTask">CoreConverterTask</a> type that is being realized.</dd><dt>errorMessage</dt><dd>Type: System.String<br />The error message of the realized task.</dd><dt>elapsedTime</dt><dd>Type: System.String<br />The total elapsed time of the realized task.</dd><dt>exitCode</dt><dd>Type: System.Int32<br />The process exit code.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterExitedEventArgs">CoreConverterExitedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_DBpoweramp_Eventing">DevCase.ThirdParty.DBpoweramp.Eventing Namespace</a><br />