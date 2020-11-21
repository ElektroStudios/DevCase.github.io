# CoreConverterProgressEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterProgressEventArgs">CoreConverterProgressEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DBpoweramp_Eventing">DevCase.ThirdParty.DBpoweramp.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CoreConverterProgressEventArgs(
	string inputFile,
	string outputFile,
	CoreConverterTask task,
	int percent
)
```

**VB**<br />
``` VB
Public Sub New ( 
	inputFile As String,
	outputFile As String,
	task As CoreConverterTask,
	percent As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim inputFile As String
Dim outputFile As String
Dim task As CoreConverterTask
Dim percent As Integer

Dim instance As New CoreConverterProgressEventArgs(inputFile, 
	outputFile, task, percent)
```

**C++**<br />
``` C++
public:
CoreConverterProgressEventArgs(
	String^ inputFile, 
	String^ outputFile, 
	CoreConverterTask task, 
	int percent
)
```

**F#**<br />
``` F#
new : 
        inputFile : string * 
        outputFile : string * 
        task : CoreConverterTask * 
        percent : int -> CoreConverterProgressEventArgs
```


#### Parameters
&nbsp;<dl><dt>inputFile</dt><dd>Type: System.String<br />The filepath that was passed as argument to the process.</dd><dt>outputFile</dt><dd>Type: System.String<br />The filepath of the file being converted.</dd><dt>task</dt><dd>Type: <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterTask">DevCase.ThirdParty.DBpoweramp.CoreConverterTask</a><br />The <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterTask">CoreConverterTask</a> type that is being realized.</dd><dt>percent</dt><dd>Type: System.Int32<br />The `CoreConverter.exe` task percent done.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterProgressEventArgs">CoreConverterProgressEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_DBpoweramp_Eventing">DevCase.ThirdParty.DBpoweramp.Eventing Namespace</a><br />