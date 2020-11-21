# DevCheckBoxStateLayout.TickColor Property 
 

Gets or sets the color of the checkbox tick.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevCheckBoxData">DevCase.Controls.DevCheckBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Color), "ControlText")]
public Color TickColor { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Color), "ControlText")>
Public Property TickColor As Color
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevCheckBoxStateLayout
Dim value As Color

value = instance.TickColor

instance.TickColor = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Color), L"ControlText")]
property Color TickColor {
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
member TickColor : Color with get, set

```


#### Property Value
Type: Color<br />The color of the checkbox tick.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout">DevCheckBoxStateLayout Class</a><br /><a href="N_DevCase_Controls_DevCheckBoxData">DevCase.Controls.DevCheckBoxData Namespace</a><br />