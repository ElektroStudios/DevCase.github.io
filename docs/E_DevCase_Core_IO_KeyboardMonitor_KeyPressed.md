# KeyboardMonitor.KeyPressed Event
 

Occurs when a key is pressed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<KeyPressedEventArgs> KeyPressed
```

**VB**<br />
``` VB
Public Event KeyPressed As EventHandler(Of KeyPressedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardMonitor
Dim handler As EventHandler(Of KeyPressedEventArgs)

AddHandler instance.KeyPressed, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<KeyPressedEventArgs^>^ KeyPressed {
	void add (EventHandler<KeyPressedEventArgs^>^ value);
	void remove (EventHandler<KeyPressedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member KeyPressed : IEvent<EventHandler<KeyPressedEventArgs>,
    KeyPressedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Core_IO_Eventing_KeyPressedEventArgs">KeyPressedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Core_IO_KeyboardMonitor">KeyboardMonitor Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />