# MP3GainWrapper.Started Event
 

Event raised when the `MP3Gain.exe` process has been started.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MP3GainStartedEventArgs> Started
```

**VB**<br />
``` VB
Public Event Started As EventHandler(Of MP3GainStartedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3GainWrapper
Dim handler As EventHandler(Of MP3GainStartedEventArgs)

AddHandler instance.Started, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MP3GainStartedEventArgs^>^ Started {
	void add (EventHandler<MP3GainStartedEventArgs^>^ value);
	void remove (EventHandler<MP3GainStartedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Started : IEvent<EventHandler<MP3GainStartedEventArgs>,
    MP3GainStartedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainStartedEventArgs">MP3GainStartedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Gain_MP3GainWrapper">MP3GainWrapper Class</a><br /><a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain Namespace</a><br />