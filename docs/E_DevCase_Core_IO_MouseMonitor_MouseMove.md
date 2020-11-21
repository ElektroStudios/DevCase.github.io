# MouseMonitor.MouseMove Event
 

Occurs when the mouse moves.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MouseMoveEventArgs> MouseMove
```

**VB**<br />
``` VB
Public Event MouseMove As EventHandler(Of MouseMoveEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseMonitor
Dim handler As EventHandler(Of MouseMoveEventArgs)

AddHandler instance.MouseMove, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MouseMoveEventArgs^>^ MouseMove {
	void add (EventHandler<MouseMoveEventArgs^>^ value);
	void remove (EventHandler<MouseMoveEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member MouseMove : IEvent<EventHandler<MouseMoveEventArgs>,
    MouseMoveEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_IO_Eventing_MouseMoveEventArgs">MouseMoveEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseMonitor">MouseMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />