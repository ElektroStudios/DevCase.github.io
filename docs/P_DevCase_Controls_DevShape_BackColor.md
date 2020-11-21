# DevShape.BackColor Property 
 

Gets or sets the background color of the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[BindableAttribute(true)]
[DefaultValueAttribute(typeof(Color), "Transparent")]
public override Color BackColor { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<BindableAttribute(true)>
<DefaultValueAttribute(GetType(Color), "Transparent")>
Public Overrides Property BackColor As Color
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevShape
Dim value As Color

value = instance.BackColor

instance.BackColor = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[BindableAttribute(true)]
[DefaultValueAttribute(typeof(Color), L"Transparent")]
virtual property Color BackColor {
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
[<DefaultValueAttribute(typeof(Color), "Transparent")>]
abstract BackColor : Color with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<BindableAttribute(true)>]
[<DefaultValueAttribute(typeof(Color), "Transparent")>]
override BackColor : Color with get, set
```


#### Property Value
Type: Color<br />The background color of the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevShape">DevShape Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />