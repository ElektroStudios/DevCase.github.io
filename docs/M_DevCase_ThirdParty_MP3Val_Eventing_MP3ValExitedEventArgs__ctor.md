# MP3ValExitedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs">MP3ValExitedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Val_Eventing">DevCase.ThirdParty.MP3Val.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public MP3ValExitedEventArgs(
	string arguments,
	string file,
	MP3ValTask task,
	string infoMessage,
	List<string> warnings,
	List<string> errors,
	bool fileNeedFix,
	bool fileIsFixed,
	int exitCode
)
```

**VB**<br />
``` VB
Public Sub New ( 
	arguments As String,
	file As String,
	task As MP3ValTask,
	infoMessage As String,
	warnings As List(Of String),
	errors As List(Of String),
	fileNeedFix As Boolean,
	fileIsFixed As Boolean,
	exitCode As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim arguments As String
Dim file As String
Dim task As MP3ValTask
Dim infoMessage As String
Dim warnings As List(Of String)
Dim errors As List(Of String)
Dim fileNeedFix As Boolean
Dim fileIsFixed As Boolean
Dim exitCode As Integer

Dim instance As New MP3ValExitedEventArgs(arguments, 
	file, task, infoMessage, warnings, 
	errors, fileNeedFix, fileIsFixed, 
	exitCode)
```

**C++**<br />
``` C++
public:
MP3ValExitedEventArgs(
	String^ arguments, 
	String^ file, 
	MP3ValTask task, 
	String^ infoMessage, 
	List<String^>^ warnings, 
	List<String^>^ errors, 
	bool fileNeedFix, 
	bool fileIsFixed, 
	int exitCode
)
```

**F#**<br />
``` F#
new : 
        arguments : string * 
        file : string * 
        task : MP3ValTask * 
        infoMessage : string * 
        warnings : List<string> * 
        errors : List<string> * 
        fileNeedFix : bool * 
        fileIsFixed : bool * 
        exitCode : int -> MP3ValExitedEventArgs
```


#### Parameters
&nbsp;<dl><dt>arguments</dt><dd>Type: System.String<br />The arguments that was passed to the process.</dd><dt>file</dt><dd>Type: System.String<br />The source audio filepath that was passed to the process.</dd><dt>task</dt><dd>Type: <a href="T_DevCase_ThirdParty_MP3Val_MP3ValTask">DevCase.ThirdParty.MP3Val.MP3ValTask</a><br />The MP3Val task that is being realized.</dd><dt>infoMessage</dt><dd>Type: System.String<br />The info message of the realized task.</dd><dt>warnings</dt><dd>Type: System.Collections.Generic.List(String)<br />The warning messages (if any).</dd><dt>errors</dt><dd>Type: System.Collections.Generic.List(String)<br />The error messages (if any).</dd><dt>fileNeedFix</dt><dd>Type: System.Boolean<br />A value indicating whether the source audio need to be fixed.</dd><dt>fileIsFixed</dt><dd>Type: System.Boolean<br />A value indicating whether the source audio file was fixed.</dd><dt>exitCode</dt><dd>Type: System.Int32<br />The process exit code.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs">MP3ValExitedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_MP3Val_Eventing">DevCase.ThirdParty.MP3Val.Eventing Namespace</a><br />