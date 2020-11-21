# FfmpegProgressEventArgs Constructor 
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegProgressEventArgs">FfmpegProgressEventArgs</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ffmpeg_Eventing">DevCase.ThirdParty.Ffmpeg.Eventing</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FfmpegProgressEventArgs(
	string file,
	FfmpegTask task,
	int percent,
	double writtenBytes,
	TimeSpan videoDuration,
	TimeSpan time
)
```

**VB**<br />
``` VB
Public Sub New ( 
	file As String,
	task As FfmpegTask,
	percent As Integer,
	writtenBytes As Double,
	videoDuration As TimeSpan,
	time As TimeSpan
)
```

**VB Usage**<br />
``` VB Usage
Dim file As String
Dim task As FfmpegTask
Dim percent As Integer
Dim writtenBytes As Double
Dim videoDuration As TimeSpan
Dim time As TimeSpan

Dim instance As New FfmpegProgressEventArgs(file, task, 
	percent, writtenBytes, videoDuration, 
	time)
```

**C++**<br />
``` C++
public:
FfmpegProgressEventArgs(
	String^ file, 
	FfmpegTask task, 
	int percent, 
	double writtenBytes, 
	TimeSpan videoDuration, 
	TimeSpan time
)
```

**F#**<br />
``` F#
new : 
        file : string * 
        task : FfmpegTask * 
        percent : int * 
        writtenBytes : float * 
        videoDuration : TimeSpan * 
        time : TimeSpan -> FfmpegProgressEventArgs
```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.String<br />The filepath that was passed as argument to the process.</dd><dt>task</dt><dd>Type: <a href="T_DevCase_ThirdParty_Ffmpeg_FfmpegTask">DevCase.ThirdParty.Ffmpeg.FfmpegTask</a><br />The <a href="T_DevCase_ThirdParty_Ffmpeg_FfmpegTask">FfmpegTask</a> type that is being realized.</dd><dt>percent</dt><dd>Type: System.Int32<br />The `FFMPEG.exe` task percent done.</dd><dt>writtenBytes</dt><dd>Type: System.Double<br />The total amount of written bytes.</dd><dt>videoDuration</dt><dd>Type: System.TimeSpan<br />The input video duration.</dd><dt>time</dt><dd>Type: System.TimeSpan<br />The processed video time.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegProgressEventArgs">FfmpegProgressEventArgs Class</a><br /><a href="N_DevCase_ThirdParty_Ffmpeg_Eventing">DevCase.ThirdParty.Ffmpeg.Eventing Namespace</a><br />