# KeyboardMonitor.HotkeyPastePressed Event
 

Occurs when a paste hotkey is pressed (`Ctrl`+`V`).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<HotkeyPastePressedEventArgs> HotkeyPastePressed
```

**VB**<br />
``` VB
Public Event HotkeyPastePressed As EventHandler(Of HotkeyPastePressedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardMonitor
Dim handler As EventHandler(Of HotkeyPastePressedEventArgs)

AddHandler instance.HotkeyPastePressed, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<HotkeyPastePressedEventArgs^>^ HotkeyPastePressed {
	void add (EventHandler<HotkeyPastePressedEventArgs^>^ value);
	void remove (EventHandler<HotkeyPastePressedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member HotkeyPastePressed : IEvent<EventHandler<HotkeyPastePressedEventArgs>,
    HotkeyPastePressedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_IO_Eventing_HotkeyPastePressedEventArgs">HotkeyPastePressedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_IO_KeyboardMonitor">KeyboardMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />