# DevComboBoxStateLayout.Cursor Property 
 

Gets the cursor that appears when the pointer moves over the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_DevComboBoxData">DevCase.Controls.DevComboBoxData</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Cursor), "Default")]
public Cursor Cursor { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Cursor), "Default")>
Public Property Cursor As Cursor
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevComboBoxStateLayout
Dim value As Cursor

value = instance.Cursor

instance.Cursor = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Cursor), L"Default")]
property Cursor^ Cursor {
	Cursor^ get ();
	void set (Cursor^ value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Cursor), "Default")>]
member Cursor : Cursor with get, set

```


#### Property Value
Type: Cursor<br />The cursor that appears when the pointer moves over the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevComboBoxData_DevComboBoxStateLayout">DevComboBoxStateLayout Class</a><br /><a href="N_DevCase_Controls_DevComboBoxData">DevCase.Controls.DevComboBoxData Namespace</a><br />