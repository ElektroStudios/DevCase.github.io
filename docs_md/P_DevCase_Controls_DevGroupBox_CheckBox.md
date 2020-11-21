# DevGroupBox.CheckBox Property 
 

Gets the child <a href="T_DevCase_Controls_DevCheckBox">DevCheckBox</a> control that is shown on the header of this <a href="T_DevCase_Controls_DevGroupBox">DevGroupBox</a> control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Advanced)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)]
public virtual DevCheckBox CheckBox { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>
Public Overridable ReadOnly Property CheckBox As DevCheckBox
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevGroupBox
Dim value As DevCheckBox

value = instance.CheckBox

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Advanced)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Content)]
virtual property DevCheckBox^ CheckBox {
	DevCheckBox^ get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
abstract CheckBox : DevCheckBox with get
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
override CheckBox : DevCheckBox with get
```


#### Property Value
Type: <a href="T_DevCase_Controls_DevCheckBox">DevCheckBox</a><br />The child <a href="T_DevCase_Controls_DevCheckBox">DevCheckBox</a> control that is shown on the header of this <a href="T_DevCase_Controls_DevGroupBox">DevGroupBox</a> control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevGroupBox">DevGroupBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />