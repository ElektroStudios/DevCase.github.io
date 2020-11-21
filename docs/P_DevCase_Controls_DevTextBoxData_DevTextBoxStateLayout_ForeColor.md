# DevTextBoxStateLayout.ForeColor Property 
 

Gets or sets the foreground color of the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevTextBoxData">DevCase.Controls.DevTextBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Color), "ControlText")]
public Color ForeColor { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Color), "ControlText")>
Public Property ForeColor As Color
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevTextBoxStateLayout
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
[DefaultValueAttribute(typeof(Color), L"ControlText")]
property Color ForeColor {
	Color get ();
	void set (Color value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Color), "ControlText")>]
member ForeColor : Color with get, set

```


#### Property Value
Type: Color<br />The foreground color of the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevTextBoxData_DevTextBoxStateLayout">DevTextBoxStateLayout Class</a><br /><a href="N_DevCase_Controls_DevTextBoxData">DevCase.Controls.DevTextBoxData Namespace</a><br />