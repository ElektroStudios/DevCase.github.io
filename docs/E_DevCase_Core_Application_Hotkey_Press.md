# Hotkey.Press Event
 

Occurs when the hotkey is pressed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<HotkeyPressEventArgs> Press
```

**VB**<br />
``` VB
Public Event Press As EventHandler(Of HotkeyPressEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Hotkey
Dim handler As EventHandler(Of HotkeyPressEventArgs)

AddHandler instance.Press, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<HotkeyPressEventArgs^>^ Press {
	void add (EventHandler<HotkeyPressEventArgs^>^ value);
	void remove (EventHandler<HotkeyPressEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Press : IEvent<EventHandler<HotkeyPressEventArgs>,
    HotkeyPressEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_Application_Eventing_HotkeyPressEventArgs">HotkeyPressEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Hotkey">Hotkey Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />