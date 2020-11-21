# DevListBoxItemLayoutColors.NormalAlternate Property 
 

Gets or sets the alternate background color to use for non-selected items.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevListBoxData">DevCase.Controls.DevListBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Color), "")]
public Color NormalAlternate { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Color), "")>
Public Property NormalAlternate As Color
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListBoxItemLayoutColors
Dim value As Color

value = instance.NormalAlternate

instance.NormalAlternate = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Color), L"")]
property Color NormalAlternate {
	Color get ();
	void set (Color value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Color), "")>]
member NormalAlternate : Color with get, set

```


#### Property Value
Type: Color<br />The alternate background color to use for non-selected items.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListBoxData_DevListBoxItemLayoutColors">DevListBoxItemLayoutColors Class</a><br /><a href="N_DevCase_Controls_DevListBoxData">DevCase.Controls.DevListBoxData Namespace</a><br />