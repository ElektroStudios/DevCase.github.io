# DevColorDialog.Location Property 
 

Gets or sets the location, in screen coordinates, of the dialog window.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Point), "0,0")]
public virtual Point Location { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Point), "0,0")>
Public Overridable Property Location As Point
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevColorDialog
Dim value As Point

value = instance.Location

instance.Location = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Point), L"0,0")]
virtual property Point Location {
	Point get ();
	void set (Point value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Point), "0,0")>]
abstract Location : Point with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Point), "0,0")>]
override Location : Point with get, set
```


#### Property Value
Type: Point<br />The location, in screen coordinates, of the dialog window.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevColorDialog">DevColorDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />