# DevRichTextBox.StateEnabled Property 
 

Gets the appearance layout of the control when it is enabled.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)]
public virtual DevRichTextBoxStateLayout StateEnabled { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>
Public Overridable ReadOnly Property StateEnabled As DevRichTextBoxStateLayout
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevRichTextBox
Dim value As DevRichTextBoxStateLayout

value = instance.StateEnabled

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Content)]
virtual property DevRichTextBoxStateLayout^ StateEnabled {
	DevRichTextBoxStateLayout^ get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
abstract StateEnabled : DevRichTextBoxStateLayout with get
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
override StateEnabled : DevRichTextBoxStateLayout with get
```


#### Property Value
Type: <a href="T_DevCase_Controls_DevRichTextBoxData_DevRichTextBoxStateLayout">DevRichTextBoxStateLayout</a><br />The appearance layout of the control when it is enabled.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevRichTextBox">DevRichTextBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />