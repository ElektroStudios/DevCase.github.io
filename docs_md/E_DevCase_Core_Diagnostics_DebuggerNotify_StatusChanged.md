# DebuggerNotify.StatusChanged Event
 

Occurs when a debugger is attached to or detached from the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<DebuggerNotifyEventArgs> StatusChanged
```

**VB**<br />
``` VB
Public Event StatusChanged As EventHandler(Of DebuggerNotifyEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DebuggerNotify
Dim handler As EventHandler(Of DebuggerNotifyEventArgs)

AddHandler instance.StatusChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<DebuggerNotifyEventArgs^>^ StatusChanged {
	void add (EventHandler<DebuggerNotifyEventArgs^>^ value);
	void remove (EventHandler<DebuggerNotifyEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member StatusChanged : IEvent<EventHandler<DebuggerNotifyEventArgs>,
    DebuggerNotifyEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_Diagnostics_DebuggerNotifyEventArgs">DebuggerNotifyEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_DebuggerNotify">DebuggerNotify Class</a><br /><a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />