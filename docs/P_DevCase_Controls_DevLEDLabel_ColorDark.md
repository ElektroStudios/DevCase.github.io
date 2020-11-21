# DevLEDLabel.ColorDark Property 
 

Gets or sets the color of the LED light back.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Color), "DimGray")]
public virtual Color ColorDark { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Color), "DimGray")>
Public Overridable Property ColorDark As Color
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLEDLabel
Dim value As Color

value = instance.ColorDark

instance.ColorDark = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Color), L"DimGray")]
virtual property Color ColorDark {
	Color get ();
	void set (Color value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Color), "DimGray")>]
abstract ColorDark : Color with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Color), "DimGray")>]
override ColorDark : Color with get, set
```


#### Property Value
Type: Color<br />The color of the LED light back.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLEDLabel">DevLEDLabel Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />