# DevRichTextBoxBorderLayout.Enabled Property 
 

Gets or sets a value indicating whether the border of the control is shown.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevRichTextBoxData">DevCase.Controls.DevRichTextBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(bool), "True")]
public bool Enabled { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Boolean), "True")>
Public Property Enabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevRichTextBoxBorderLayout
Dim value As Boolean

value = instance.Enabled

instance.Enabled = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(bool), L"True")]
property bool Enabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(bool), "True")>]
member Enabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the border of the control is shown; otherwise `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_DevRichTextBoxData_DevRichTextBoxBorderLayout">DevRichTextBoxBorderLayout Class</a><br /><a href="N_DevCase_Controls_DevRichTextBoxData">DevCase.Controls.DevRichTextBoxData Namespace</a><br />