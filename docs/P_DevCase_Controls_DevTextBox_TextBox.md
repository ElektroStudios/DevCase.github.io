# DevTextBox.TextBox Property 
 

Gets the child TextBox control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Advanced)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)]
public virtual TextBox TextBox { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>
Public Overridable ReadOnly Property TextBox As TextBox
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevTextBox
Dim value As TextBox

value = instance.TextBox

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Advanced)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Content)]
virtual property TextBox^ TextBox {
	TextBox^ get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
abstract TextBox : TextBox with get
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Content)>]
override TextBox : TextBox with get
```


#### Property Value
Type: TextBox<br />The child TextBox control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevTextBox">DevTextBox Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />