# DevAltitudeSelector.AltitudeChanged Event
 

Occurs when the altitude has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<EventArgs> AltitudeChanged
```

**VB**<br />
``` VB
Public Event AltitudeChanged As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevAltitudeSelector
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.AltitudeChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<EventArgs^>^ AltitudeChanged {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
member AltitudeChanged : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Controls_DevAltitudeSelector">DevAltitudeSelector Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />