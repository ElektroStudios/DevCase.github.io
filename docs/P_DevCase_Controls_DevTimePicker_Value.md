# DevTimePicker.Value Property 
 

Gets or sets the time value assigned to the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BindableAttribute(true)]
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public TimeSpan Value { get; set; }
```

**VB**<br />
``` VB
<BindableAttribute(true)>
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Property Value As TimeSpan
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevTimePicker
Dim value As TimeSpan

value = instance.Value

instance.Value = value
```

**C++**<br />
``` C++
public:
[BindableAttribute(true)]
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
property TimeSpan Value {
	TimeSpan get ();
	void set (TimeSpan value);
}
```

**F#**<br />
``` F#
[<BindableAttribute(true)>]
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member Value : TimeSpan with get, set

```


#### Property Value
Type: TimeSpan<br />The time value assigned to the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevTimePicker">DevTimePicker Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />