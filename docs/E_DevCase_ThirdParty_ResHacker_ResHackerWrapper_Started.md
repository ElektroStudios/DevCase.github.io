# ResHackerWrapper.Started Event
 

Event raised when the `ResHacker.exe` process has been started.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<ResHackerStartedEventArgs> Started
```

**VB**<br />
``` VB
Public Event Started As EventHandler(Of ResHackerStartedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResHackerWrapper
Dim handler As EventHandler(Of ResHackerStartedEventArgs)

AddHandler instance.Started, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<ResHackerStartedEventArgs^>^ Started {
	void add (EventHandler<ResHackerStartedEventArgs^>^ value);
	void remove (EventHandler<ResHackerStartedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Started : IEvent<EventHandler<ResHackerStartedEventArgs>,
    ResHackerStartedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_ResHacker_Eventing_ResHackerStartedEventArgs">ResHackerStartedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ResHacker_ResHackerWrapper">ResHackerWrapper Class</a><br /><a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker Namespace</a><br />