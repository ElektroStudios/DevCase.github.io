# DevImageComboBox.ImageMember Property 
 

Gets or sets the Image member to display for this control using a data source with DataSource

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Cursor), "Default")]
public virtual string ImageMember { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Cursor), "Default")>
Public Overridable Property ImageMember As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevImageComboBox
Dim value As String

value = instance.ImageMember

instance.ImageMember = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Cursor), L"Default")]
virtual property String^ ImageMember {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Cursor), "Default")>]
abstract ImageMember : string with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Cursor), "Default")>]
override ImageMember : string with get, set
```


#### Property Value
Type: String<br />The Image member to display for this control using a data source.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevImageComboBox">DevImageComboBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />