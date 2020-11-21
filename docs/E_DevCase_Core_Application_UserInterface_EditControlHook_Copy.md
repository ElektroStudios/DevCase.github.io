# EditControlHook.Copy Event
 

Occurs when the text of the control is copied.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<EventArgs> Copy
```

**VB**<br />
``` VB
Public Event Copy As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As EditControlHook
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.Copy, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<EventArgs^>^ Copy {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
member Copy : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_EditControlHook">EditControlHook Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />