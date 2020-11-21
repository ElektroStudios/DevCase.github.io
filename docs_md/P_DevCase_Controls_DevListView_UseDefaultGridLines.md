# DevListView.UseDefaultGridLines Property 
 

Gets or sets a value indicating whether the control should draw default grid lines.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(bool), "False")]
public bool UseDefaultGridLines { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Boolean), "False")>
Public Property UseDefaultGridLines As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListView
Dim value As Boolean

value = instance.UseDefaultGridLines

instance.UseDefaultGridLines = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(bool), L"False")]
property bool UseDefaultGridLines {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(bool), "False")>]
member UseDefaultGridLines : bool with get, set

```


#### Property Value
Type: Boolean<br />A value indicating whether the control should draw default grid lines.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListView">DevListView Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />