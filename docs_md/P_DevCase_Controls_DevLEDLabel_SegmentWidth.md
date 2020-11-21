# DevLEDLabel.SegmentWidth Property 
 

Gets or sets the width of the LED segments.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(int), "10")]
public virtual int SegmentWidth { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Integer), "10")>
Public Overridable Property SegmentWidth As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLEDLabel
Dim value As Integer

value = instance.SegmentWidth

instance.SegmentWidth = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(int), L"10")]
virtual property int SegmentWidth {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(int), "10")>]
abstract SegmentWidth : int with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(int), "10")>]
override SegmentWidth : int with get, set
```


#### Property Value
Type: Int32<br />The width of the LED segments.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLEDLabel">DevLEDLabel Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />