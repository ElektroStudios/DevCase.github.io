# NativeWindowEventNotifier.Resize Event
 

Occurs when the owner window is resizing.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<EventArgs> Resize
```

**VB**<br />
``` VB
Public Event Resize As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As NativeWindowEventNotifier
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.Resize, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<EventArgs^>^ Resize {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Resize : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_NativeWindowEventNotifier">NativeWindowEventNotifier Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />