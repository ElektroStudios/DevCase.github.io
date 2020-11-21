# CoreConverterStartedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterStartedEventArgs">CoreConverterStartedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DBpoweramp_Eventing">DevCase.ThirdParty.DBpoweramp.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CoreConverterStartedEventArgs(
	string inputFile,
	string outputFile,
	CoreConverterTask task
)
```

**VB**<br />
``` VB
Public Sub New ( 
	inputFile As String,
	outputFile As String,
	task As CoreConverterTask
)
```

**VB Usage**<br />
``` VB Usage
Dim inputFile As String
Dim outputFile As String
Dim task As CoreConverterTask

Dim instance As New CoreConverterStartedEventArgs(inputFile, 
	outputFile, task)
```

**C++**<br />
``` C++
public:
CoreConverterStartedEventArgs(
	String^ inputFile, 
	String^ outputFile, 
	CoreConverterTask task
)
```

**F#**<br />
``` F#
new : 
        inputFile : string * 
        outputFile : string * 
        task : CoreConverterTask -> CoreConverterStartedEventArgs
```


#### Parameters
&nbsp;<dl><dt>inputFile</dt><dd>Type: System.String<br />The filepath that was passed as argument to the process.</dd><dt>outputFile</dt><dd>Type: System.String<br />The filepath of the file being converted.</dd><dt>task</dt><dd>Type: <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterTask">DevCase.ThirdParty.DBpoweramp.CoreConverterTask</a><br />The <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterTask">CoreConverterTask</a> type that is being realized.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DBpoweramp_Eventing_CoreConverterStartedEventArgs">CoreConverterStartedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_DBpoweramp_Eventing">DevCase.ThirdParty.DBpoweramp.Eventing Namespace</a><br />