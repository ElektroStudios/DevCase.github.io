# DevRichTextBoxBorderLayout.ColorNormal Property 
 

Gets or sets the border color of the control when it is not focused.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevRichTextBoxData">DevCase.Controls.DevRichTextBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Color), "ControlDark")]
public Color ColorNormal { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Color), "ControlDark")>
Public Property ColorNormal As Color
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevRichTextBoxBorderLayout
Dim value As Color

value = instance.ColorNormal

instance.ColorNormal = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Color), L"ControlDark")]
property Color ColorNormal {
	Color get ();
	void set (Color value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Color), "ControlDark")>]
member ColorNormal : Color with get, set

```


#### Property Value
Type: Color<br />The border color of the control when it is not focused.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevRichTextBoxData_DevRichTextBoxBorderLayout">DevRichTextBoxBorderLayout Class</a><br /><a href="N_DevCase_Controls_DevRichTextBoxData">DevCase.Controls.DevRichTextBoxData Namespace</a><br />