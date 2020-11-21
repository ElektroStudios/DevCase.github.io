# MouseHook.MouseWheel Event
 

Occurs when the mouse wheel is moved up or down.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event MouseHook.MouseWheelEventHandler MouseWheel
```

**VB**<br />
``` VB
Public Event MouseWheel As MouseHook.MouseWheelEventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseHook
Dim handler As MouseHook.MouseWheelEventHandler

AddHandler instance.MouseWheel, handler

```

**C++**<br />
``` C++
public:
 event MouseHook.MouseWheelEventHandler^ MouseWheel {
	void add (MouseHook.MouseWheelEventHandler^ value);
	void remove (MouseHook.MouseWheelEventHandler^ value);
}
```

**F#**<br />
``` F#
member MouseWheel : IEvent<MouseHook.MouseWheelEventHandler,
    MouseWheelDirection>

```


#### Value
Type: <a href="T_DevCase_Core_IO_MouseHook_MouseWheelEventHandler">DevCase.Core.IO.MouseHook.MouseWheelEventHandler</a>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseHook">MouseHook Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />