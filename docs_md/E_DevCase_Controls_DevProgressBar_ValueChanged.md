# DevProgressBar.ValueChanged Event
 

Occurs when the progress bar value changes.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public event EventHandler<ProgressBarValueChangedEventArgs> ValueChanged
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Event ValueChanged As EventHandler(Of ProgressBarValueChangedEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressBar
Dim handler As EventHandler(Of ProgressBarValueChangedEventArgs)

AddHandler instance.ValueChanged, handler

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
 event EventHandler<ProgressBarValueChangedEventArgs^>^ ValueChanged {
	void add (EventHandler<ProgressBarValueChangedEventArgs^>^ value);
	void remove (EventHandler<ProgressBarValueChangedEventArgs^>^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member ValueChanged : IEvent<EventHandler<ProgressBarValueChangedEventArgs>,
    ProgressBarValueChangedEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Controls_Eventing_ProgressBarValueChangedEventArgs">ProgressBarValueChangedEventArgs</a>)

## Examples
This is a code example. 
**VB**<br />
``` VB
''' ----------------------------------------------------------------------------------------------------
''' <summary>
''' Handles the <see cref="ElektroProgressBar.ValueChanged"/> event of the <see cref="ElektroProgressBar1"/> control.
''' </summary>
''' ----------------------------------------------------------------------------------------------------
''' <param name="sender">
''' The source of the event.
''' </param>
''' 
''' <param name="e">
''' The <see cref="ProgressBarValueChangedEventArgs"/> instance containing the event data.
''' </param>
''' ----------------------------------------------------------------------------------------------------
Private Sub ElektroProgressBar1_ValueChanged(sender As Object, e As ProgressBarValueChangedEventArgs) _
Handles ElektroProgressBar1.ValueChanged

    ' Dim pb As DevProgressBar = DirectCast(sender, ElektroProgressBar)
    Console.WriteLine(e.NewValue)

End Sub
```


## See Also


#### Reference
<a href="T_DevCase_Controls_DevProgressBar">DevProgressBar Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />