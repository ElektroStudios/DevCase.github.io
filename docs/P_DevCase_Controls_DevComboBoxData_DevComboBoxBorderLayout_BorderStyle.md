# DevComboBoxBorderLayout.BorderStyle Property 
 

Gets or sets the border style of the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevComboBoxData">DevCase.Controls.DevComboBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(ButtonBorderStyle), "Solid")]
public ButtonBorderStyle BorderStyle { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(ButtonBorderStyle), "Solid")>
Public Property BorderStyle As ButtonBorderStyle
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevComboBoxBorderLayout
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
property ButtonBorderStyle BorderStyle {
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
member BorderStyle : ButtonBorderStyle with get, set

```


#### Property Value
Type: ButtonBorderStyle<br />The border style of the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevComboBoxData_DevComboBoxBorderLayout">DevComboBoxBorderLayout Class</a><br /><a href="N_DevCase_Controls_DevComboBoxData">DevCase.Controls.DevComboBoxData Namespace</a><br />