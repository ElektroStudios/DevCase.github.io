# DevNumericUpDown.StateReadOnly Property 
 

Gets the appearance layout of the control when it is in read-only mode.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)]
public virtual DevNumericUpDownStateLayout StateReadOnly { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>
Public Overridable ReadOnly Property StateReadOnly As DevNumericUpDownStateLayout
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevNumericUpDown
Dim value As DevNumericUpDownStateLayout

value = instance.StateReadOnly

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Content)]
virtual property DevNumericUpDownStateLayout^ StateReadOnly {
	DevNumericUpDownStateLayout^ get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
abstract StateReadOnly : DevNumericUpDownStateLayout with get
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
override StateReadOnly : DevNumericUpDownStateLayout with get
```


#### Property Value
Type: <a href="T_DevCase_Controls_DevNumericUpDownData_DevNumericUpDownStateLayout">DevNumericUpDownStateLayout</a><br />The appearance layout of the control when it is in read-only mode.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevNumericUpDown">DevNumericUpDown Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />