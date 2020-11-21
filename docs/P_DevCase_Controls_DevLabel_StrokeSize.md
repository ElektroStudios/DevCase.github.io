# DevLabel.StrokeSize Property 
 

Gets or sets the size of the stroke.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(float), "1.0F")]
public virtual float StrokeSize { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Single), "1.0F")>
Public Overridable Property StrokeSize As Single
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLabel
Dim value As Single

value = instance.StrokeSize

instance.StrokeSize = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(float), L"1.0F")]
virtual property float StrokeSize {
	float get ();
	void set (float value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(float32), "1.0F")>]
abstract StrokeSize : float32 with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(float32), "1.0F")>]
override StrokeSize : float32 with get, set
```


#### Property Value
Type: Single<br />The size of the stroke.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLabel">DevLabel Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />