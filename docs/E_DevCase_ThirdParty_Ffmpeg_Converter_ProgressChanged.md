# Converter.ProgressChanged Event
 

Event raised when `FFMPEG.exe` task progress has been changed.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<FfmpegProgressEventArgs> ProgressChanged
```

**VB**<br />
``` VB
Public Event ProgressChanged As EventHandler(Of FfmpegProgressEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Converter
Dim handler As EventHandler(Of FfmpegProgressEventArgs)

AddHandler instance.ProgressChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<FfmpegProgressEventArgs^>^ ProgressChanged {
	void add (EventHandler<FfmpegProgressEventArgs^>^ value);
	void remove (EventHandler<FfmpegProgressEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member ProgressChanged : IEvent<EventHandler<FfmpegProgressEventArgs>,
    FfmpegProgressEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegProgressEventArgs">FfmpegProgressEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Ffmpeg_Converter">Converter Class</a><br /><a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg Namespace</a><br />