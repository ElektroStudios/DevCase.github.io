# Converter.Started Event
 

Event raised when the `FFMPEG.exe` process has been started.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<FfmpegStartedEventArgs> Started
```

**VB**<br />
``` VB
Public Event Started As EventHandler(Of FfmpegStartedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Converter
Dim handler As EventHandler(Of FfmpegStartedEventArgs)

AddHandler instance.Started, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<FfmpegStartedEventArgs^>^ Started {
	void add (EventHandler<FfmpegStartedEventArgs^>^ value);
	void remove (EventHandler<FfmpegStartedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Started : IEvent<EventHandler<FfmpegStartedEventArgs>,
    FfmpegStartedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegStartedEventArgs">FfmpegStartedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Ffmpeg_Converter">Converter Class</a><br /><a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg Namespace</a><br />