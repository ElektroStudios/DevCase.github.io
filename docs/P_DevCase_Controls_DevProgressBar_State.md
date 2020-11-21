# DevProgressBar.State Property 
 

Gets or sets the state (and fill color) of the progress bar.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(DevProgressBarState), "Normal")]
public virtual DevProgressBarState State { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(DevProgressBarState), "Normal")>
Public Overridable Property State As DevProgressBarState
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressBar
Dim value As DevProgressBarState

value = instance.State

instance.State = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(DevProgressBarState), L"Normal")]
virtual property DevProgressBarState State {
	DevProgressBarState get ();
	void set (DevProgressBarState value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(DevProgressBarState), "Normal")>]
abstract State : DevProgressBarState with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(DevProgressBarState), "Normal")>]
override State : DevProgressBarState with get, set
```


#### Property Value
Type: <a href="T_DevCase_Controls_DevProgressBarData_DevProgressBarState">DevProgressBarState</a><br />The state (and fill color) of the progress bar.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevProgressBar">DevProgressBar Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />