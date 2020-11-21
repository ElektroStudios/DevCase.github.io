# DevCheckBox.StateDisabled Property 
 

Gets the appearance layout of the control when it is disabled.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)]
public virtual DevCheckBoxStateLayout StateDisabled { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>
Public Overridable ReadOnly Property StateDisabled As DevCheckBoxStateLayout
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevCheckBox
Dim value As DevCheckBoxStateLayout

value = instance.StateDisabled

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Content)]
virtual property DevCheckBoxStateLayout^ StateDisabled {
	DevCheckBoxStateLayout^ get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
abstract StateDisabled : DevCheckBoxStateLayout with get
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
override StateDisabled : DevCheckBoxStateLayout with get
```


#### Property Value
Type: <a href="T_DevCase_Controls_DevCheckBoxData_DevCheckBoxStateLayout">DevCheckBoxStateLayout</a><br />The appearance layout of the control when it is disabled.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevCheckBox">DevCheckBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />