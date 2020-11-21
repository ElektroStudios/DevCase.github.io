# MkvMergeWrapper.Started Event
 

Event raised when the `MkvMerge.exe` process has been started.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MkvToolnix">DevCase.ThirdParty.MkvToolnix</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MkvMergeStartedEventArgs> Started
```

**VB**<br />
``` VB
Public Event Started As EventHandler(Of MkvMergeStartedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MkvMergeWrapper
Dim handler As EventHandler(Of MkvMergeStartedEventArgs)

AddHandler instance.Started, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MkvMergeStartedEventArgs^>^ Started {
	void add (EventHandler<MkvMergeStartedEventArgs^>^ value);
	void remove (EventHandler<MkvMergeStartedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Started : IEvent<EventHandler<MkvMergeStartedEventArgs>,
    MkvMergeStartedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_ThirdParty_MkvToolnix_Eventing_MkvMergeStartedEventArgs">MkvMergeStartedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MkvToolnix_MkvMergeWrapper">MkvMergeWrapper Class</a><br /><a href="N_DevCase_ThirdParty_MkvToolnix">DevCase.ThirdParty.MkvToolnix Namespace</a><br />