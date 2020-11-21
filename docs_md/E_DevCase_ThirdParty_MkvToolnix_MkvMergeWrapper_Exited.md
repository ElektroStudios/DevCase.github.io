# MkvMergeWrapper.Exited Event
 

Event raised when the `MkvMerge.exe` process has exited.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MkvToolnix">DevCase.ThirdParty.MkvToolnix</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MkvMergeExitedEventArgs> Exited
```

**VB**<br />
``` VB
Public Event Exited As EventHandler(Of MkvMergeExitedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MkvMergeWrapper
Dim handler As EventHandler(Of MkvMergeExitedEventArgs)

AddHandler instance.Exited, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MkvMergeExitedEventArgs^>^ Exited {
	void add (EventHandler<MkvMergeExitedEventArgs^>^ value);
	void remove (EventHandler<MkvMergeExitedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Exited : IEvent<EventHandler<MkvMergeExitedEventArgs>,
    MkvMergeExitedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_MkvToolnix_Eventing_MkvMergeExitedEventArgs">MkvMergeExitedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MkvToolnix_MkvMergeWrapper">MkvMergeWrapper Class</a><br /><a href="N_DevCase_ThirdParty_MkvToolnix">DevCase.ThirdParty.MkvToolnix Namespace</a><br />