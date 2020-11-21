# DevLEDLabel.TextChanged Event
 

Occurs when the text changes.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public event EventHandler<EventArgs> TextChanged
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Event TextChanged As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLEDLabel
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.TextChanged, handler

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
 event EventHandler<EventArgs^>^ TextChanged {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member TextChanged : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLEDLabel">DevLEDLabel Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />