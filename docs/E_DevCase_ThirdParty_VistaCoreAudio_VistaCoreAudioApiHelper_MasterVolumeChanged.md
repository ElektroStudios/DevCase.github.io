# VistaCoreAudioApiHelper.MasterVolumeChanged Event
 

Event raised when device master-volume changes.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MasterVolumeChangedEventArgs> MasterVolumeChanged
```

**VB**<br />
``` VB
Public Event MasterVolumeChanged As EventHandler(Of MasterVolumeChangedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VistaCoreAudioApiHelper
Dim handler As EventHandler(Of MasterVolumeChangedEventArgs)

AddHandler instance.MasterVolumeChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MasterVolumeChangedEventArgs^>^ MasterVolumeChanged {
	void add (EventHandler<MasterVolumeChangedEventArgs^>^ value);
	void remove (EventHandler<MasterVolumeChangedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member MasterVolumeChanged : IEvent<EventHandler<MasterVolumeChangedEventArgs>,
    MasterVolumeChangedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_VistaCoreAudio_Eventing_MasterVolumeChangedEventArgs">MasterVolumeChangedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper">VistaCoreAudioApiHelper Class</a><br /><a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio Namespace</a><br />