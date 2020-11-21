# DevShape.SmoothingMode Property 
 

Gets or sets the rendering quality of the shape.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(SmoothingMode), "Default")]
public SmoothingMode SmoothingMode { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(SmoothingMode), "Default")>
Public Property SmoothingMode As SmoothingMode
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevShape
Dim value As SmoothingMode

value = instance.SmoothingMode

instance.SmoothingMode = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(SmoothingMode), L"Default")]
property SmoothingMode SmoothingMode {
	SmoothingMode get ();
	void set (SmoothingMode value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(SmoothingMode), "Default")>]
member SmoothingMode : SmoothingMode with get, set

```


#### Property Value
Type: SmoothingMode<br />The rendering quality of the shape.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevShape">DevShape Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />