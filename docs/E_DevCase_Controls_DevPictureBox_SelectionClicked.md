# DevPictureBox.SelectionClicked Event
 

Occurs when the user clicks inside the selection rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event MouseEventHandler SelectionClicked
```

**VB**<br />
``` VB
Public Event SelectionClicked As MouseEventHandler
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevPictureBox
Dim handler As MouseEventHandler

AddHandler instance.SelectionClicked, handler

```

**C++**<br />
``` C++
public:
 event MouseEventHandler^ SelectionClicked {
	void add (MouseEventHandler^ value);
	void remove (MouseEventHandler^ value);
}
```

**F#**<br />
``` F#
member SelectionClicked : IEvent<MouseEventHandler,
    MouseEventArgs>

```


#### Value
Type: System.Windows.Forms.MouseEventHandler

## See Also


#### Reference
<a href="T_DevCase_Controls_DevPictureBox">DevPictureBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />