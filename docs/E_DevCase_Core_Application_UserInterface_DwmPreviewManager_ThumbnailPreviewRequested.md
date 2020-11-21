# DwmPreviewManager.ThumbnailPreviewRequested Event
 

Occurs when Windows requested to display a thumbnail preview on the Taskbar or window manager (`ALT+TAB`) menu.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<EventArgs> ThumbnailPreviewRequested
```

**VB**<br />
``` VB
Public Event ThumbnailPreviewRequested As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DwmPreviewManager
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.ThumbnailPreviewRequested, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<EventArgs^>^ ThumbnailPreviewRequested {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
member ThumbnailPreviewRequested : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_DwmPreviewManager">DwmPreviewManager Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />