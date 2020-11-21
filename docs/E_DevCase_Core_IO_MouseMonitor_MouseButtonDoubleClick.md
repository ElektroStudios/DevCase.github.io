# MouseMonitor.MouseButtonDoubleClick Event
 

Occurs when a mouse button is clicked twice producing a double-click.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MouseButtonDoubleClickEventArgs> MouseButtonDoubleClick
```

**VB**<br />
``` VB
Public Event MouseButtonDoubleClick As EventHandler(Of MouseButtonDoubleClickEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseMonitor
Dim handler As EventHandler(Of MouseButtonDoubleClickEventArgs)

AddHandler instance.MouseButtonDoubleClick, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MouseButtonDoubleClickEventArgs^>^ MouseButtonDoubleClick {
	void add (EventHandler<MouseButtonDoubleClickEventArgs^>^ value);
	void remove (EventHandler<MouseButtonDoubleClickEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member MouseButtonDoubleClick : IEvent<EventHandler<MouseButtonDoubleClickEventArgs>,
    MouseButtonDoubleClickEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_IO_Eventing_MouseButtonDoubleClickEventArgs">MouseButtonDoubleClickEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseMonitor">MouseMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />