# DevTextBox.StateReadOnly Property 
 

Gets the appearance layout of the control when it is in read-only mode.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)]
public virtual DevTextBoxStateLayout StateReadOnly { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>
Public Overridable ReadOnly Property StateReadOnly As DevTextBoxStateLayout
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevTextBox
Dim value As DevTextBoxStateLayout

value = instance.StateReadOnly

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Content)]
virtual property DevTextBoxStateLayout^ StateReadOnly {
	DevTextBoxStateLayout^ get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
abstract StateReadOnly : DevTextBoxStateLayout with get
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
override StateReadOnly : DevTextBoxStateLayout with get
```


#### Property Value
Type: <a href="T_DevCase_Controls_DevTextBoxData_DevTextBoxStateLayout">DevTextBoxStateLayout</a><br />The appearance layout of the control when it is in read-only mode.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevTextBox">DevTextBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />