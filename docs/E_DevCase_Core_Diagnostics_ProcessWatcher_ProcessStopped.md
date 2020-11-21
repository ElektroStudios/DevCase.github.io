# ProcessWatcher.ProcessStopped Event
 

Occurs when a process stops (exit).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventArrivedEventHandler ProcessStopped
```

**VB**<br />
``` VB
Public Event ProcessStopped As EventArrivedEventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessWatcher
Dim handler As EventArrivedEventHandler

AddHandler instance.ProcessStopped, handler

```

**C++**<br />
``` C++
public:
 event EventArrivedEventHandler^ ProcessStopped {
	void add (EventArrivedEventHandler^ value);
	void remove (EventArrivedEventHandler^ value);
}
```

**F#**<br />
``` F#
member ProcessStopped : IEvent<EventArrivedEventHandler,
    EventArrivedEventArgs>

```


#### Value
Type: System.Management.EventArrivedEventHandler

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_ProcessWatcher">ProcessWatcher Class</a><br /><a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />