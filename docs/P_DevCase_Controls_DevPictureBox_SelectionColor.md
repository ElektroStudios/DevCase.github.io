# DevPictureBox.SelectionColor Property 
 

Gets or sets the color used to draw the selection rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Color), "Color.FromArgb(128, 72, 145, 220)")]
public Color SelectionColor { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Color), "Color.FromArgb(128, 72, 145, 220)")>
Public Property SelectionColor As Color
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevPictureBox
Dim value As Color

value = instance.SelectionColor

instance.SelectionColor = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Color), L"Color.FromArgb(128, 72, 145, 220)")]
property Color SelectionColor {
	Color get ();
	void set (Color value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Color), "Color.FromArgb(128, 72, 145, 220)")>]
member SelectionColor : Color with get, set

```


#### Property Value
Type: Color<br />The color used to draw the selection rectangle.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevPictureBox">DevPictureBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />