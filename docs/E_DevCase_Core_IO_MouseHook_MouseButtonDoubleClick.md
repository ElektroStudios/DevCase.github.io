# MouseHook.MouseButtonDoubleClick Event
 

Occurs when the mouse performs a double-click on a button. 

 A double click is considered as: (MouseButtonDown + MouseButtonUp) * 2

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event MouseHook.MouseButtonDoubleClickEventHandler MouseButtonDoubleClick
```

**VB**<br />
``` VB
Public Event MouseButtonDoubleClick As MouseHook.MouseButtonDoubleClickEventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseHook
Dim handler As MouseHook.MouseButtonDoubleClickEventHandler

AddHandler instance.MouseButtonDoubleClick, handler

```

**C++**<br />
``` C++
public:
 event MouseHook.MouseButtonDoubleClickEventHandler^ MouseButtonDoubleClick {
	void add (MouseHook.MouseButtonDoubleClickEventHandler^ value);
	void remove (MouseHook.MouseButtonDoubleClickEventHandler^ value);
}
```

**F#**<br />
``` F#
member MouseButtonDoubleClick : IEvent<MouseHook.MouseButtonDoubleClickEventHandler,
    EventArgs>

```


#### Value
Type: <a href="T_DevCase_Core_IO_MouseHook_MouseButtonDoubleClickEventHandler">DevCase.Core.IO.MouseHook.MouseButtonDoubleClickEventHandler</a>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseHook">MouseHook Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />