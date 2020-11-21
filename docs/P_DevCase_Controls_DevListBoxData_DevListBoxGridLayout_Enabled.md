# DevListBoxGridLayout.Enabled Property 
 

Gets or sets a value indicating whether grid lines drawing are enabled to separate items.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevListBoxData">DevCase.Controls.DevListBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(bool), "False")]
public bool Enabled { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Boolean), "False")>
Public Property Enabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListBoxGridLayout
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
[DefaultValueAttribute(typeof(bool), L"False")]
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
[<DefaultValueAttribute(typeof(bool), "False")>]
member Enabled : bool with get, set

```


#### Property Value
Type: Boolean<br />A value indicating whether grid lines drawing are enabled to separate items.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListBoxData_DevListBoxGridLayout">DevListBoxGridLayout Class</a><br /><a href="N_DevCase_Controls_DevListBoxData">DevCase.Controls.DevListBoxData Namespace</a><br />