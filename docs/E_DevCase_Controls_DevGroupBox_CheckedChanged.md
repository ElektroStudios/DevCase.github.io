# DevGroupBox.CheckedChanged Event
 

Occurs when the checked state of the <a href="P_DevCase_Controls_DevGroupBox_CheckBox">CheckBox</a> has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public event EventHandler<EventArgs> CheckedChanged
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Event CheckedChanged As EventHandler(Of EventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevGroupBox
Dim handler As EventHandler(Of EventArgs)

AddHandler instance.CheckedChanged, handler

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
 event EventHandler<EventArgs^>^ CheckedChanged {
	void add (EventHandler<EventArgs^>^ value);
	void remove (EventHandler<EventArgs^>^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member CheckedChanged : IEvent<EventHandler<EventArgs>,
    EventArgs>

```


#### Value
Type: System.EventHandler(EventArgs)

## See Also


#### Reference
<a href="T_DevCase_Controls_DevGroupBox">DevGroupBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />