# MouseHook.MouseButtonClick Event
 

Occurs when a mouse button is pressed or released.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event MouseHook.MouseButtonClickEventHandler MouseButtonClick
```

**VB**<br />
``` VB
Public Event MouseButtonClick As MouseHook.MouseButtonClickEventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseHook
Dim handler As MouseHook.MouseButtonClickEventHandler

AddHandler instance.MouseButtonClick, handler

```

**C++**<br />
``` C++
public:
 event MouseHook.MouseButtonClickEventHandler^ MouseButtonClick {
	void add (MouseHook.MouseButtonClickEventHandler^ value);
	void remove (MouseHook.MouseButtonClickEventHandler^ value);
}
```

**F#**<br />
``` F#
member MouseButtonClick : IEvent<MouseHook.MouseButtonClickEventHandler,
    EventArgs>

```


#### Value
Type: <a href="T_DevCase_Core_IO_MouseHook_MouseButtonClickEventHandler">DevCase.Core.IO.MouseHook.MouseButtonClickEventHandler</a>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseHook">MouseHook Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />