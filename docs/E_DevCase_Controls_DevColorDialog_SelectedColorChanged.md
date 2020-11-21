# DevColorDialog.SelectedColorChanged Event
 

Occurs when the current selected color has changed.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public event EventHandler<ColorChangedEventArgs> SelectedColorChanged
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Event SelectedColorChanged As EventHandler(Of ColorChangedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevColorDialog
Dim handler As EventHandler(Of ColorChangedEventArgs)

AddHandler instance.SelectedColorChanged, handler

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
 event EventHandler<ColorChangedEventArgs^>^ SelectedColorChanged {
	void add (EventHandler<ColorChangedEventArgs^>^ value);
	void remove (EventHandler<ColorChangedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member SelectedColorChanged : IEvent<EventHandler<ColorChangedEventArgs>,
    ColorChangedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Controls_Eventing_ColorChangedEventArgs">ColorChangedEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Controls_DevColorDialog">DevColorDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />