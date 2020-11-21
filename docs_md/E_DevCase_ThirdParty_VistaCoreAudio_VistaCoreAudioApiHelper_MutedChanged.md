# VistaCoreAudioApiHelper.MutedChanged Event
 

Event raised when device muting changes.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MutedChangedEventArgs> MutedChanged
```

**VB**<br />
``` VB
Public Event MutedChanged As EventHandler(Of MutedChangedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As VistaCoreAudioApiHelper
Dim handler As EventHandler(Of MutedChangedEventArgs)

AddHandler instance.MutedChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MutedChangedEventArgs^>^ MutedChanged {
	void add (EventHandler<MutedChangedEventArgs^>^ value);
	void remove (EventHandler<MutedChangedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member MutedChanged : IEvent<EventHandler<MutedChangedEventArgs>,
    MutedChangedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_VistaCoreAudio_Eventing_MutedChangedEventArgs">MutedChangedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VistaCoreAudio_VistaCoreAudioApiHelper">VistaCoreAudioApiHelper Class</a><br /><a href="N_DevCase_ThirdParty_VistaCoreAudio">DevCase.ThirdParty.VistaCoreAudio Namespace</a><br />