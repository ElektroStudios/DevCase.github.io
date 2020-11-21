# FfmpegExitedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegExitedEventArgs">FfmpegExitedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ffmpeg_Eventing">DevCase.ThirdParty.Ffmpeg.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FfmpegExitedEventArgs(
	string file,
	FfmpegTask task,
	List<string> errors,
	int exitCode
)
```

**VB**<br />
``` VB
Public Sub New ( 
	file As String,
	task As FfmpegTask,
	errors As List(Of String),
	exitCode As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim file As String
Dim task As FfmpegTask
Dim errors As List(Of String)
Dim exitCode As Integer

Dim instance As New FfmpegExitedEventArgs(file, task, 
	errors, exitCode)
```

**C++**<br />
``` C++
public:
FfmpegExitedEventArgs(
	String^ file, 
	FfmpegTask task, 
	List<String^>^ errors, 
	int exitCode
)
```

**F#**<br />
``` F#
new : 
        file : string * 
        task : FfmpegTask * 
        errors : List<string> * 
        exitCode : int -> FfmpegExitedEventArgs
```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.String<br />The filepath that was passed as argument to the process.</dd><dt>task</dt><dd>Type: <a href="T_DevCase_ThirdParty_Ffmpeg_FfmpegTask">DevCase.ThirdParty.Ffmpeg.FfmpegTask</a><br />The <a href="T_DevCase_ThirdParty_Ffmpeg_FfmpegTask">FfmpegTask</a> type that is being realized.</dd><dt>errors</dt><dd>Type: System.Collections.Generic.List(String)<br />The error messages of the realized task (if any).</dd><dt>exitCode</dt><dd>Type: System.Int32<br />The process exit code.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegExitedEventArgs">FfmpegExitedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_Ffmpeg_Eventing">DevCase.ThirdParty.Ffmpeg.Eventing Namespace</a><br />