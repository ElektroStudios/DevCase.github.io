# MP3ValWrapper.Exited Event
 

Event raised when the `MP3Val.exe` process has exited.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Val">DevCase.ThirdParty.MP3Val</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MP3ValExitedEventArgs> Exited
```

**VB**<br />
``` VB
Public Event Exited As EventHandler(Of MP3ValExitedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3ValWrapper
Dim handler As EventHandler(Of MP3ValExitedEventArgs)

AddHandler instance.Exited, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MP3ValExitedEventArgs^>^ Exited {
	void add (EventHandler<MP3ValExitedEventArgs^>^ value);
	void remove (EventHandler<MP3ValExitedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Exited : IEvent<EventHandler<MP3ValExitedEventArgs>,
    MP3ValExitedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_MP3Val_Eventing_MP3ValExitedEventArgs">MP3ValExitedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Val_MP3ValWrapper">MP3ValWrapper Class</a><br /><a href="N_DevCase_ThirdParty_MP3Val">DevCase.ThirdParty.MP3Val Namespace</a><br />