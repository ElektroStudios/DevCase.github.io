# DevLEDBulb.ActivatedChanged Event
 

Occurs when the LED state has changed to ON or OFF.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public event EventHandler<EventArgs> ActivatedChanged
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Event ActivatedChanged As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLEDBulb
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.ActivatedChanged, handler

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
 event EventHandler<EventArgs^>^ ActivatedChanged {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member ActivatedChanged : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLEDBulb">DevLEDBulb Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />