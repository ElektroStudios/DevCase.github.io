# DevAngleSelector.AngleChanged Event
 

Occurs when the angle has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<EventArgs> AngleChanged
```

**VB**<br />
``` VB
Public Event AngleChanged As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevAngleSelector
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.AngleChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<EventArgs^>^ AngleChanged {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
member AngleChanged : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Controls_DevAngleSelector">DevAngleSelector Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />