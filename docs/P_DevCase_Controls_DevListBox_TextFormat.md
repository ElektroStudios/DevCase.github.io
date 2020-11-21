# DevListBox.TextFormat Property 
 

Gets the text formatting layout for the items in the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)]
public virtual DevListBoxStringFormatLayout TextFormat { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>
Public Overridable ReadOnly Property TextFormat As DevListBoxStringFormatLayout
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevListBox
Dim value As DevListBoxStringFormatLayout

value = instance.TextFormat

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Content)]
virtual property DevListBoxStringFormatLayout^ TextFormat {
	DevListBoxStringFormatLayout^ get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
abstract TextFormat : DevListBoxStringFormatLayout with get
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
override TextFormat : DevListBoxStringFormatLayout with get
```


#### Property Value
Type: <a href="T_DevCase_Controls_DevListBoxData_DevListBoxStringFormatLayout">DevListBoxStringFormatLayout</a><br />The text formatting layout for the items in the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevListBox">DevListBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />