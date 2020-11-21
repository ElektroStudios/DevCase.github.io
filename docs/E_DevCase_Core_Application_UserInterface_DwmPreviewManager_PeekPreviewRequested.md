# DwmPreviewManager.PeekPreviewRequested Event
 

Occurs when Windows requested to display a live (`Aero Peek`) preview on the Taskbar or window manager (`ALT+TAB`) menu.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<EventArgs> PeekPreviewRequested
```

**VB**<br />
``` VB
Public Event PeekPreviewRequested As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DwmPreviewManager
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.PeekPreviewRequested, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<EventArgs^>^ PeekPreviewRequested {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
member PeekPreviewRequested : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_DwmPreviewManager">DwmPreviewManager Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />