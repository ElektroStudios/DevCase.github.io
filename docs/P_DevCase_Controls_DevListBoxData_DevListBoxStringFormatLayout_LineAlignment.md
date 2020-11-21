# DevListBoxStringFormatLayout.LineAlignment Property 
 

Gets or sets the line alignment of a text string relative to its layout rectangle.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevListBoxData">DevCase.Controls.DevListBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(StringAlignment), "Center")]
public StringAlignment LineAlignment { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(StringAlignment), "Center")>
Public Property LineAlignment As StringAlignment
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListBoxStringFormatLayout
Dim value As StringAlignment

value = instance.LineAlignment

instance.LineAlignment = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(StringAlignment), L"Center")]
property StringAlignment LineAlignment {
	StringAlignment get ();
	void set (StringAlignment value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(StringAlignment), "Center")>]
member LineAlignment : StringAlignment with get, set

```


#### Property Value
Type: StringAlignment<br />The line alignment of a text string relative to its layout rectangle.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListBoxData_DevListBoxStringFormatLayout">DevListBoxStringFormatLayout Class</a><br /><a href="N_DevCase_Controls_DevListBoxData">DevCase.Controls.DevListBoxData Namespace</a><br />