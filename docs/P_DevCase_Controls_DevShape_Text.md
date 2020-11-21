# DevShape.Text Property 
 

Gets or sets the text associated with the shape.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[BindableAttribute(true)]
[DefaultValueAttribute(typeof(string), "")]
public override string Text { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<BindableAttribute(true)>
<DefaultValueAttribute(GetType(String), "")>
Public Overrides Property Text As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevShape
Dim value As String

value = instance.Text

instance.Text = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[BindableAttribute(true)]
[DefaultValueAttribute(typeof(String), L"")]
virtual property String^ Text {
	String^ get () override;
	void set (String^ value) override;
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<BindableAttribute(true)>]
[<DefaultValueAttribute(typeof(string), "")>]
abstract Text : string with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<BindableAttribute(true)>]
[<DefaultValueAttribute(typeof(string), "")>]
override Text : string with get, set
```


#### Property Value
Type: String<br />The text associated with the shape.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevShape">DevShape Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />