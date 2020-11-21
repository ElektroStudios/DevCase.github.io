# FfmpegStartedEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegStartedEventArgs">FfmpegStartedEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ffmpeg_Eventing">DevCase.ThirdParty.Ffmpeg.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FfmpegStartedEventArgs(
	string file,
	FfmpegTask task
)
```

**VB**<br />
``` VB
Public Sub New ( 
	file As String,
	task As FfmpegTask
)
```

**VB Usage**<br />
``` VB Usage
Dim file As String
Dim task As FfmpegTask

Dim instance As New FfmpegStartedEventArgs(file, task)
```

**C++**<br />
``` C++
public:
FfmpegStartedEventArgs(
	String^ file, 
	FfmpegTask task
)
```

**F#**<br />
``` F#
new : 
        file : string * 
        task : FfmpegTask -> FfmpegStartedEventArgs
```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.String<br />The filepath that was passed as argument to the process.</dd><dt>task</dt><dd>Type: <a href="T_DevCase_ThirdParty_Ffmpeg_FfmpegTask">DevCase.ThirdParty.Ffmpeg.FfmpegTask</a><br />The <a href="T_DevCase_ThirdParty_Ffmpeg_FfmpegTask">FfmpegTask</a> type that is being realized.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegStartedEventArgs">FfmpegStartedEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_Ffmpeg_Eventing">DevCase.ThirdParty.Ffmpeg.Eventing Namespace</a><br />