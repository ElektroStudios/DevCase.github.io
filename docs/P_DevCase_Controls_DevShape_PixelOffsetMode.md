# DevShape.PixelOffsetMode Property 
 

Gets or set a value indicating how pixels are offset during rendering the shape.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(PixelOffsetMode), "Default")]
public PixelOffsetMode PixelOffsetMode { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(PixelOffsetMode), "Default")>
Public Property PixelOffsetMode As PixelOffsetMode
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevShape
Dim value As PixelOffsetMode

value = instance.PixelOffsetMode

instance.PixelOffsetMode = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(PixelOffsetMode), L"Default")]
property PixelOffsetMode PixelOffsetMode {
	PixelOffsetMode get ();
	void set (PixelOffsetMode value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(PixelOffsetMode), "Default")>]
member PixelOffsetMode : PixelOffsetMode with get, set

```


#### Property Value
Type: PixelOffsetMode<br />A value indicating how pixels are offset during rendering the shape.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevShape">DevShape Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />