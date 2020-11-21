# DevPictureBox.ImageChanged Event
 

Occurs when the value of the <a href="P_DevCase_Controls_DevPictureBox_Image">Image</a> property changes.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler ImageChanged
```

**VB**<br />
``` VB
Public Event ImageChanged As EventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevPictureBox
Dim handler As EventHandler

AddHandler instance.ImageChanged, handler

```

**C++**<br />
``` C++
public:
 event EventHandler^ ImageChanged {
	void add (EventHandler^ value);
	void remove (EventHandler^ value);
}
```

**F#**<br />
``` F#
member ImageChanged : IEvent<EventHandler,
    EventArgs>

```


#### Value
Type: System.EventHandler

## See Also


#### Reference
<a href="T_DevCase_Controls_DevPictureBox">DevPictureBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />