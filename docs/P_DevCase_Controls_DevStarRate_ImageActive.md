# DevStarRate.ImageActive Property 
 

Gets or sets the image to display fot the active rating shapes.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Image), "")]
public virtual Image ImageActive { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Image), "")>
Public Overridable Property ImageActive As Image
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevStarRate
Dim value As Image

value = instance.ImageActive

instance.ImageActive = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Image), L"")]
virtual property Image^ ImageActive {
	Image^ get ();
	void set (Image^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Image), "")>]
abstract ImageActive : Image with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Image), "")>]
override ImageActive : Image with get, set
```


#### Property Value
Type: Image<br />The image to display fot the active rating shapes.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevStarRate">DevStarRate Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />