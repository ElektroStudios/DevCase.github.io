# ProcessMonitor.ProcessStarted Event
 

Occurs when a process starts.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<ProcessMonitorEventArgs> ProcessStarted
```

**VB**<br />
``` VB
Public Event ProcessStarted As EventHandler(Of ProcessMonitorEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessMonitor
Dim handler As EventHandler(Of ProcessMonitorEventArgs)

AddHandler instance.ProcessStarted, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<ProcessMonitorEventArgs^>^ ProcessStarted {
	void add (EventHandler<ProcessMonitorEventArgs^>^ value);
	void remove (EventHandler<ProcessMonitorEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member ProcessStarted : IEvent<EventHandler<ProcessMonitorEventArgs>,
    ProcessMonitorEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_Diagnostics_Eventing_ProcessMonitorEventArgs">ProcessMonitorEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_ProcessMonitor">ProcessMonitor Class</a><br /><a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />