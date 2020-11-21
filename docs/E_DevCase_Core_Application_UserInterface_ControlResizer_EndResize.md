# ControlResizer.EndResize Event
 

Occurs when when the control ends resizing.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<EventArgs> EndResize
```

**VB**<br />
``` VB
Public Event EndResize As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlResizer
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.EndResize, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<EventArgs^>^ EndResize {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
member EndResize : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlResizer">ControlResizer Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />