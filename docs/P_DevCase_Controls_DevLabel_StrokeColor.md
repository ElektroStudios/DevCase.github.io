# DevLabel.StrokeColor Property 
 

Gets or sets the stroke color.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Color), "Black")]
public Color StrokeColor { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Color), "Black")>
Public Property StrokeColor As Color
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLabel
Dim value As Color

value = instance.StrokeColor

instance.StrokeColor = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Color), L"Black")]
property Color StrokeColor {
	Color get ();
	void set (Color value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Color), "Black")>]
member StrokeColor : Color with get, set

```


#### Property Value
Type: Color<br />The stroke color.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLabel">DevLabel Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />