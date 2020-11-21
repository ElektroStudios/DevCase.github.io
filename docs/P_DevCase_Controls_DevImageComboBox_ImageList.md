# DevImageComboBox.ImageList Property 
 

Gets or sets the ImageList that contains the images displayed in the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(ImageList), "")]
public virtual ImageList ImageList { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(ImageList), "")>
Public Overridable Property ImageList As ImageList
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevImageComboBox
Dim value As ImageList

value = instance.ImageList

instance.ImageList = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(ImageList), L"")]
virtual property ImageList^ ImageList {
	ImageList^ get ();
	void set (ImageList^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(ImageList), "")>]
abstract ImageList : ImageList with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(ImageList), "")>]
override ImageList : ImageList with get, set
```


#### Property Value
Type: ImageList<br />The ImageList that contains the images displayed in the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevImageComboBox">DevImageComboBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />