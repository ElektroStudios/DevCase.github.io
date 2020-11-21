# DevPictureBox.Image Property 
 

Gets the image displayed in the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[BindableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public Image Image { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<BindableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Property Image As Image
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevPictureBox
Dim value As Image

value = instance.Image

instance.Image = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[BindableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
property Image^ Image {
	Image^ get ();
	void set (Image^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<BindableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member Image : Image with get, set

```


#### Property Value
Type: Image<br />The image displayed in the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevPictureBox">DevPictureBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />