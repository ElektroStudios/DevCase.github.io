# MP3ValWrapper.Started Event
 

Event raised when the `MP3Val.exe` process has been started.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Val">DevCase.ThirdParty.MP3Val</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MP3ValStartedEventArgs> Started
```

**VB**<br />
``` VB
Public Event Started As EventHandler(Of MP3ValStartedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3ValWrapper
Dim handler As EventHandler(Of MP3ValStartedEventArgs)

AddHandler instance.Started, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MP3ValStartedEventArgs^>^ Started {
	void add (EventHandler<MP3ValStartedEventArgs^>^ value);
	void remove (EventHandler<MP3ValStartedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Started : IEvent<EventHandler<MP3ValStartedEventArgs>,
    MP3ValStartedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_MP3Val_Eventing_MP3ValStartedEventArgs">MP3ValStartedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Val_MP3ValWrapper">MP3ValWrapper Class</a><br /><a href="N_DevCase_ThirdParty_MP3Val">DevCase.ThirdParty.MP3Val Namespace</a><br />