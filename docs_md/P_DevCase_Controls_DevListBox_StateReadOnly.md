# DevListBox.StateReadOnly Property 
 

Gets the appearance layout for the control when it is in read-only mode.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)]
public virtual DevListBoxStateLayout StateReadOnly { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>
Public Overridable ReadOnly Property StateReadOnly As DevListBoxStateLayout
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListBox
Dim value As DevListBoxStateLayout

value = instance.StateReadOnly

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Content)]
virtual property DevListBoxStateLayout^ StateReadOnly {
	DevListBoxStateLayout^ get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
abstract StateReadOnly : DevListBoxStateLayout with get
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
override StateReadOnly : DevListBoxStateLayout with get
```


#### Property Value
Type: <a href="T_DevCase_Controls_DevListBoxData_DevListBoxStateLayout">DevListBoxStateLayout</a><br />The appearance layout for the control when it is in read-only mode.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListBox">DevListBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />