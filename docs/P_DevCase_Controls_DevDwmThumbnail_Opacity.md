# DevDwmThumbnail.Opacity Property 
 

Gets or sets the opacity level of the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[TypeConverterAttribute(typeof(OpacityConverter))]
[DefaultValueAttribute(typeof(double), "1.0")]
public virtual double Opacity { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<TypeConverterAttribute(GetType(OpacityConverter))>
<DefaultValueAttribute(GetType(Double), "1.0")>
Public Overridable Property Opacity As Double
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevDwmThumbnail
Dim value As Double

value = instance.Opacity

instance.Opacity = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[TypeConverterAttribute(typeof(OpacityConverter))]
[DefaultValueAttribute(typeof(double), L"1.0")]
virtual property double Opacity {
	double get ();
	void set (double value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<TypeConverterAttribute(typeof(OpacityConverter))>]
[<DefaultValueAttribute(typeof(float), "1.0")>]
abstract Opacity : float with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<TypeConverterAttribute(typeof(OpacityConverter))>]
[<DefaultValueAttribute(typeof(float), "1.0")>]
override Opacity : float with get, set
```


#### Property Value
Type: Double<br />The opacity level of the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevDwmThumbnail">DevDwmThumbnail Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />