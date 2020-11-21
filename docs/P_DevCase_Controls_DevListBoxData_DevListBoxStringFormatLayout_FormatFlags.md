# DevListBoxStringFormatLayout.FormatFlags Property 
 

Gets or sets the display and layout information for text strings.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevListBoxData">DevCase.Controls.DevListBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(StringFormatFlags), "NoWrap")]
public StringFormatFlags FormatFlags { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(StringFormatFlags), "NoWrap")>
Public Property FormatFlags As StringFormatFlags
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListBoxStringFormatLayout
Dim value As StringFormatFlags

value = instance.FormatFlags

instance.FormatFlags = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(StringFormatFlags), L"NoWrap")]
property StringFormatFlags FormatFlags {
	StringFormatFlags get ();
	void set (StringFormatFlags value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(StringFormatFlags), "NoWrap")>]
member FormatFlags : StringFormatFlags with get, set

```


#### Property Value
Type: StringFormatFlags<br />The display and layout information for text strings.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListBoxData_DevListBoxStringFormatLayout">DevListBoxStringFormatLayout Class</a><br /><a href="N_DevCase_Controls_DevListBoxData">DevCase.Controls.DevListBoxData Namespace</a><br />