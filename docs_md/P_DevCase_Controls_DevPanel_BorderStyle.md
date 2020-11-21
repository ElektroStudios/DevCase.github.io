# DevPanel.BorderStyle Property 
 

Gets or sets the border style of the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(ButtonBorderStyle), "Solid")]
public virtual ButtonBorderStyle BorderStyle { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(ButtonBorderStyle), "Solid")>
Public Overridable Property BorderStyle As ButtonBorderStyle
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevPanel
Dim value As ButtonBorderStyle

value = instance.BorderStyle

instance.BorderStyle = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(ButtonBorderStyle), L"Solid")]
virtual property ButtonBorderStyle BorderStyle {
	ButtonBorderStyle get ();
	void set (ButtonBorderStyle value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(ButtonBorderStyle), "Solid")>]
abstract BorderStyle : ButtonBorderStyle with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(ButtonBorderStyle), "Solid")>]
override BorderStyle : ButtonBorderStyle with get, set
```


#### Property Value
Type: ButtonBorderStyle<br />The border style of the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevPanel">DevPanel Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />