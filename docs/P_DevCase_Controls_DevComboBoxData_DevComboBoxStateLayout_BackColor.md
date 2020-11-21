# DevComboBoxStateLayout.BackColor Property 
 

Gets or sets the background color of the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevComboBoxData">DevCase.Controls.DevComboBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Color), "Control")]
public Color BackColor { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Color), "Control")>
Public Property BackColor As Color
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevComboBoxStateLayout
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
[DefaultValueAttribute(typeof(Color), L"Control")]
property Color BackColor {
	Color get ();
	void set (Color value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Color), "Control")>]
member BackColor : Color with get, set

```


#### Property Value
Type: Color<br />The background color of the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevComboBoxData_DevComboBoxStateLayout">DevComboBoxStateLayout Class</a><br /><a href="N_DevCase_Controls_DevComboBoxData">DevCase.Controls.DevComboBoxData Namespace</a><br />