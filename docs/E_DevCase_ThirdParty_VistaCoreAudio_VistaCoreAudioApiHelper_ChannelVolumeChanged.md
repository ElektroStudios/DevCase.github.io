# VistaCoreAudioApiHelper.ChannelVolumeChanged Event
 

Event raised when a device channel(s) volume changes

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<ChannelVolumeChangedEventArgs> ChannelVolumeChanged
```

**VB**<br />
``` VB
Public Event ChannelVolumeChanged As EventHandler(Of ChannelVolumeChangedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VistaCoreAudioApiHelper
Dim handler As EventHandler(Of ChannelVolumeChangedEventArgs)

AddHandler instance.ChannelVolumeChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<ChannelVolumeChangedEventArgs^>^ ChannelVolumeChanged {
	void add (EventHandler<ChannelVolumeChangedEventArgs^>^ value);
	void remove (EventHandler<ChannelVolumeChangedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member ChannelVolumeChanged : IEvent<EventHandler<ChannelVolumeChangedEventArgs>,
    ChannelVolumeChangedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_VistaCoreAudio_Eventing_ChannelVolumeChangedEventArgs">ChannelVolumeChangedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper">VistaCoreAudioApiHelper Class</a><br /><a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio Namespace</a><br />