# DevListBoxStringFormatLayout.Trimming Property 
 

Gets or sets a value indicating how to trim characters from a string that does not completely fit into a layout shape.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevListBoxData">DevCase.Controls.DevListBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(StringTrimming), "None")]
public StringTrimming Trimming { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(StringTrimming), "None")>
Public Property Trimming As StringTrimming
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListBoxStringFormatLayout
Dim value As StringTrimming

value = instance.Trimming

instance.Trimming = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(StringTrimming), L"None")]
property StringTrimming Trimming {
	StringTrimming get ();
	void set (StringTrimming value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(StringTrimming), "None")>]
member Trimming : StringTrimming with get, set

```


#### Property Value
Type: StringTrimming<br />A value indicating how to trim characters from a string that does not completely fit into a layout shape.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListBoxData_DevListBoxStringFormatLayout">DevListBoxStringFormatLayout Class</a><br /><a href="N_DevCase_Controls_DevListBoxData">DevCase.Controls.DevListBoxData Namespace</a><br />