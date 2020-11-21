# ResHackerWrapper.Exited Event
 

Event raised when the `ResHacker.exe` process has exited.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<ResHackerExitedEventArgs> Exited
```

**VB**<br />
``` VB
Public Event Exited As EventHandler(Of ResHackerExitedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResHackerWrapper
Dim handler As EventHandler(Of ResHackerExitedEventArgs)

AddHandler instance.Exited, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<ResHackerExitedEventArgs^>^ Exited {
	void add (EventHandler<ResHackerExitedEventArgs^>^ value);
	void remove (EventHandler<ResHackerExitedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Exited : IEvent<EventHandler<ResHackerExitedEventArgs>,
    ResHackerExitedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_ResHacker_Eventing_ResHackerExitedEventArgs">ResHackerExitedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ResHacker_ResHackerWrapper">ResHackerWrapper Class</a><br /><a href="N_DevCase_ThirdParty_ResHacker">DevCase.ThirdParty.ResHacker Namespace</a><br />