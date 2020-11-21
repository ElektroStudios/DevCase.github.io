# MouseHook.MouseMove Event
 

Occurs when the mouse moves.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event MouseHook.MouseMoveEventHandler MouseMove
```

**VB**<br />
``` VB
Public Event MouseMove As MouseHook.MouseMoveEventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseHook
Dim handler As MouseHook.MouseMoveEventHandler

AddHandler instance.MouseMove, handler

```

**C++**<br />
``` C++
public:
 event MouseHook.MouseMoveEventHandler^ MouseMove {
	void add (MouseHook.MouseMoveEventHandler^ value);
	void remove (MouseHook.MouseMoveEventHandler^ value);
}
```

**F#**<br />
``` F#
member MouseMove : IEvent<MouseHook.MouseMoveEventHandler,
    Point>

```


#### Value
Type: <a href="T_DevCase_Core_IO_MouseHook_MouseMoveEventHandler">DevCase.Core.IO.MouseHook.MouseMoveEventHandler</a>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseHook">MouseHook Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />