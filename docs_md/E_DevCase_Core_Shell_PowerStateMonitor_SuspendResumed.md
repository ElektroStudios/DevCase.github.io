# PowerStateMonitor.SuspendResumed Event
 

Occurs when the system is about to resume from Suspend state.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<EventArgs> SuspendResumed
```

**VB**<br />
``` VB
Public Event SuspendResumed As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As PowerStateMonitor
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.SuspendResumed, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<EventArgs^>^ SuspendResumed {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
member SuspendResumed : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_PowerStateMonitor">PowerStateMonitor Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />