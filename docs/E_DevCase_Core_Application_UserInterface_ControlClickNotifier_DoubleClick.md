# ControlClickNotifier.DoubleClick Event
 

Occurs when a double-click occurs in the owner <a href="P_DevCase_Core_Application_UserInterface_ControlClickNotifier_Control">Control</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<MouseEventArgs> DoubleClick
```

**VB**<br />
``` VB
Public Event DoubleClick As EventHandler(Of MouseEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlClickNotifier
Dim handler As EventHandler(Of MouseEventArgs)

AddHandler instance.DoubleClick, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<MouseEventArgs^>^ DoubleClick {
	void add (EventHandler<MouseEventArgs^>^ value);
	void remove (EventHandler<MouseEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member DoubleClick : IEvent<EventHandler<MouseEventArgs>,
    MouseEventArgs>

```


#### Value
Type: System.EventHandler(MouseEventArgs)

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ControlClickNotifier">ControlClickNotifier Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />