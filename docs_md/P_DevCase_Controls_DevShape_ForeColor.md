# DevShape.ForeColor Property 
 

Gets or sets the foreground color of the text displayed in the shape.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[BindableAttribute(true)]
[DefaultValueAttribute(typeof(Color), "ControlText")]
public override Color ForeColor { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<BindableAttribute(true)>
<DefaultValueAttribute(GetType(Color), "ControlText")>
Public Overrides Property ForeColor As Color
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevShape
Dim value As Color

value = instance.ForeColor

instance.ForeColor = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[BindableAttribute(true)]
[DefaultValueAttribute(typeof(Color), L"ControlText")]
virtual property Color ForeColor {
	Color get () override;
	void set (Color value) override;
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<BindableAttribute(true)>]
[<DefaultValueAttribute(typeof(Color), "ControlText")>]
abstract ForeColor : Color with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<BindableAttribute(true)>]
[<DefaultValueAttribute(typeof(Color), "ControlText")>]
override ForeColor : Color with get, set
```


#### Property Value
Type: Color<br />The foreground color of text displayed in the shape.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevShape">DevShape Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />