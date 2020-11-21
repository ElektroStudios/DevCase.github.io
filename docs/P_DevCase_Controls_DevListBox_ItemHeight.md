# DevListBox.ItemHeight Property 
 

Gets or sets the height of an item in the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(int), "10")]
public override int ItemHeight { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Integer), "10")>
Public Overrides Property ItemHeight As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListBox
Dim value As Integer

value = instance.ItemHeight

instance.ItemHeight = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(int), L"10")]
virtual property int ItemHeight {
	int get () override;
	void set (int value) override;
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(int), "10")>]
abstract ItemHeight : int with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(int), "10")>]
override ItemHeight : int with get, set
```


#### Property Value
Type: Int32<br />The height of an item in the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListBox">DevListBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />