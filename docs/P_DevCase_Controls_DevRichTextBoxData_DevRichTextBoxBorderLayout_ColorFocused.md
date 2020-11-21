# DevRichTextBoxBorderLayout.ColorFocused Property 
 

Gets or sets the border color of the control when it is focused.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevRichTextBoxData">DevCase.Controls.DevRichTextBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Color), "ControlLight")]
public Color ColorFocused { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Color), "ControlLight")>
Public Property ColorFocused As Color
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevRichTextBoxBorderLayout
Dim value As Color

value = instance.ColorFocused

instance.ColorFocused = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Color), L"ControlLight")]
property Color ColorFocused {
	Color get ();
	void set (Color value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Color), "ControlLight")>]
member ColorFocused : Color with get, set

```


#### Property Value
Type: Color<br />The border color of the control when it is focused.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevRichTextBoxData_DevRichTextBoxBorderLayout">DevRichTextBoxBorderLayout Class</a><br /><a href="N_DevCase_Controls_DevRichTextBoxData">DevCase.Controls.DevRichTextBoxData Namespace</a><br />