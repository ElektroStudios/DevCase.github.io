# ControlResizer.BeginResize Event
 

Occurs when when the control begin to resize.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<EventArgs> BeginResize
```

**VB**<br />
``` VB
Public Event BeginResize As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlResizer
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.BeginResize, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<EventArgs^>^ BeginResize {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
member BeginResize : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlResizer">ControlResizer Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />