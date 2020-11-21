# DevColorDialog.Text Property 
 

Gets or sets the text that will be shown on the titlebar of the dialog window.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(string), "ElektroColorDialog")]
public virtual string Text { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(String), "ElektroColorDialog")>
Public Overridable Property Text As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevColorDialog
Dim value As String

value = instance.Text

instance.Text = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(String), L"ElektroColorDialog")]
virtual property String^ Text {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(string), "ElektroColorDialog")>]
abstract Text : string with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(string), "ElektroColorDialog")>]
override Text : string with get, set
```


#### Property Value
Type: String<br />The text of the dialog window.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevColorDialog">DevColorDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />