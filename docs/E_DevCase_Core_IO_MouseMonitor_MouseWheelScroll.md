# MouseMonitor.MouseWheelScroll Event
 

Occurs when the mouse wheel scrolls up or down.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MouseWheelScrollEventArgs> MouseWheelScroll
```

**VB**<br />
``` VB
Public Event MouseWheelScroll As EventHandler(Of MouseWheelScrollEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseMonitor
Dim handler As EventHandler(Of MouseWheelScrollEventArgs)

AddHandler instance.MouseWheelScroll, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MouseWheelScrollEventArgs^>^ MouseWheelScroll {
	void add (EventHandler<MouseWheelScrollEventArgs^>^ value);
	void remove (EventHandler<MouseWheelScrollEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member MouseWheelScroll : IEvent<EventHandler<MouseWheelScrollEventArgs>,
    MouseWheelScrollEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_IO_Eventing_MouseWheelScrollEventArgs">MouseWheelScrollEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseMonitor">MouseMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />