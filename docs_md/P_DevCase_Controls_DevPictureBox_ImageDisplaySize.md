# DevPictureBox.ImageDisplaySize Property 
 

Gets the size of the image as it is shown in the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[TypeConverterAttribute(typeof(SizeConverter))]
public Size ImageDisplaySize { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<TypeConverterAttribute(GetType(SizeConverter))>
Public ReadOnly Property ImageDisplaySize As Size
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevPictureBox
Dim value As Size

value = instance.ImageDisplaySize

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[TypeConverterAttribute(typeof(SizeConverter))]
property Size ImageDisplaySize {
	Size get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<TypeConverterAttribute(typeof(SizeConverter))>]
member ImageDisplaySize : Size with get

```


#### Property Value
Type: Size<br />The size of the image as it is shown in the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevPictureBox">DevPictureBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />