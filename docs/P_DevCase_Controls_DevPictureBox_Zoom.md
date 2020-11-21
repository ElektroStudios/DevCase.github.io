# DevPictureBox.Zoom Property 
 

Gets or sets the zoom level of the image shown by the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[TypeConverterAttribute(typeof(PercentageTypeConverter))]
[DefaultValueAttribute(typeof(double), "1.0")]
public double Zoom { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<TypeConverterAttribute(GetType(PercentageTypeConverter))>
<DefaultValueAttribute(GetType(Double), "1.0")>
Public Property Zoom As Double
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevPictureBox
Dim value As Double

value = instance.Zoom

instance.Zoom = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[TypeConverterAttribute(typeof(PercentageTypeConverter))]
[DefaultValueAttribute(typeof(double), L"1.0")]
property double Zoom {
	double get ();
	void set (double value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<TypeConverterAttribute(typeof(PercentageTypeConverter))>]
[<DefaultValueAttribute(typeof(float), "1.0")>]
member Zoom : float with get, set

```


#### Property Value
Type: Double<br />The zoom level of the image shown by the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevPictureBox">DevPictureBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />