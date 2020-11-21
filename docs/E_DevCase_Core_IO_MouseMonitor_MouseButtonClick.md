# MouseMonitor.MouseButtonClick Event
 

Occurs when a mouse button is clicked.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MouseButtonClickEventArgs> MouseButtonClick
```

**VB**<br />
``` VB
Public Event MouseButtonClick As EventHandler(Of MouseButtonClickEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseMonitor
Dim handler As EventHandler(Of MouseButtonClickEventArgs)

AddHandler instance.MouseButtonClick, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MouseButtonClickEventArgs^>^ MouseButtonClick {
	void add (EventHandler<MouseButtonClickEventArgs^>^ value);
	void remove (EventHandler<MouseButtonClickEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member MouseButtonClick : IEvent<EventHandler<MouseButtonClickEventArgs>,
    MouseButtonClickEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_IO_Eventing_MouseButtonClickEventArgs">MouseButtonClickEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseMonitor">MouseMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />