# MP3GainWrapper.Exited Event
 

Event raised when the `MP3Gain.exe` process has exited.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MP3GainExitedEventArgs> Exited
```

**VB**<br />
``` VB
Public Event Exited As EventHandler(Of MP3GainExitedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MP3GainWrapper
Dim handler As EventHandler(Of MP3GainExitedEventArgs)

AddHandler instance.Exited, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MP3GainExitedEventArgs^>^ Exited {
	void add (EventHandler<MP3GainExitedEventArgs^>^ value);
	void remove (EventHandler<MP3GainExitedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Exited : IEvent<EventHandler<MP3GainExitedEventArgs>,
    MP3GainExitedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_MP3Gain_Eventing_MP3GainExitedEventArgs">MP3GainExitedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MP3Gain_MP3GainWrapper">MP3GainWrapper Class</a><br /><a href="N_DevCase_ThirdParty_MP3Gain">DevCase.ThirdParty.MP3Gain Namespace</a><br />