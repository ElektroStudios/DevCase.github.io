# Converter.Exited Event
 

Event raised when the `FFMPEG.exe` process has exited.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<FfmpegExitedEventArgs> Exited
```

**VB**<br />
``` VB
Public Event Exited As EventHandler(Of FfmpegExitedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Converter
Dim handler As EventHandler(Of FfmpegExitedEventArgs)

AddHandler instance.Exited, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<FfmpegExitedEventArgs^>^ Exited {
	void add (EventHandler<FfmpegExitedEventArgs^>^ value);
	void remove (EventHandler<FfmpegExitedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Exited : IEvent<EventHandler<FfmpegExitedEventArgs>,
    FfmpegExitedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_Ffmpeg_Eventing_FfmpegExitedEventArgs">FfmpegExitedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Ffmpeg_Converter">Converter Class</a><br /><a href="N_DevCase_ThirdParty_Ffmpeg">DevCase.ThirdParty.Ffmpeg Namespace</a><br />