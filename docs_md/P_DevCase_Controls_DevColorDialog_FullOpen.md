# DevColorDialog.FullOpen Property 
 

Gets or sets a value indicating whether the custom color section of the dialog box is initially displayed.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(bool), "True")]
public override bool FullOpen { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Boolean), "True")>
Public Overrides Property FullOpen As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevColorDialog
Dim value As Boolean

value = instance.FullOpen

instance.FullOpen = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(bool), L"True")]
virtual property bool FullOpen {
	bool get () override;
	void set (bool value) override;
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(bool), "True")>]
abstract FullOpen : bool with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(bool), "True")>]
override FullOpen : bool with get, set
```


#### Property Value
Type: Boolean<br />A value indicating whether the custom color section of the dialog box is initially displayed.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevColorDialog">DevColorDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />