# DevLEDLabelMulti.ColorLight Property 
 

Gets or sets the color of the LED light.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Color), "LawnGreen")]
public override Color ColorLight { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Color), "LawnGreen")>
Public Overrides Property ColorLight As Color
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLEDLabelMulti
Dim value As Color

value = instance.ColorLight

instance.ColorLight = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Color), L"LawnGreen")]
virtual property Color ColorLight {
	Color get () override;
	void set (Color value) override;
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Color), "LawnGreen")>]
abstract ColorLight : Color with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Color), "LawnGreen")>]
override ColorLight : Color with get, set
```


#### Property Value
Type: Color<br />The color of the LED light.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLEDLabelMulti">DevLEDLabelMulti Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />