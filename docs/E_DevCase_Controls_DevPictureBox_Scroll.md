# DevPictureBox.Scroll Event
 

Occurs when the user or code scrolls through the client area of the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event ScrollEventHandler Scroll
```

**VB**<br />
``` VB
Public Event Scroll As ScrollEventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevPictureBox
Dim handler As ScrollEventHandler

AddHandler instance.Scroll, handler

```

**C++**<br />
``` C++
public:
 event ScrollEventHandler^ Scroll {
	void add (ScrollEventHandler^ value);
	void remove (ScrollEventHandler^ value);
}
```

**F#**<br />
``` F#
member Scroll : IEvent<ScrollEventHandler,
    ScrollEventArgs>

```


#### Value
Type: System.Windows.Forms.ScrollEventHandler

## See Also


#### Reference
<a href="T_DevCase_Controls_DevPictureBox">DevPictureBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />