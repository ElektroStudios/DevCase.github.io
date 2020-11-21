# NativeWindowEventNotifier.Move Event
 

Occurs when the owner window is moving.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<EventArgs> Move
```

**VB**<br />
``` VB
Public Event Move As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As NativeWindowEventNotifier
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.Move, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<EventArgs^>^ Move {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Move : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_NativeWindowEventNotifier">NativeWindowEventNotifier Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />