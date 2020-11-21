# NetworkTrafficMonitor.TrafficChanged Event
 

Occurs when the network traffic has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<TrafficChangedEventArgs> TrafficChanged
```

**VB**<br />
``` VB
Public Event TrafficChanged As EventHandler(Of TrafficChangedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As NetworkTrafficMonitor
Dim handler As EventHandler(Of TrafficChangedEventArgs)

AddHandler instance.TrafficChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<TrafficChangedEventArgs^>^ TrafficChanged {
	void add (EventHandler<TrafficChangedEventArgs^>^ value);
	void remove (EventHandler<TrafficChangedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member TrafficChanged : IEvent<EventHandler<TrafficChangedEventArgs>,
    TrafficChangedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_NET_Eventing_TrafficChangedEventArgs">TrafficChangedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_NET_NetworkTrafficMonitor">NetworkTrafficMonitor Class</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />