# DevColorDialog.StartPosition Property 
 

Gets or sets the position of the dialog window when it first appears.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(FormStartPosition), "CenterParent")]
public virtual FormStartPosition StartPosition { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(FormStartPosition), "CenterParent")>
Public Overridable Property StartPosition As FormStartPosition
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevColorDialog
Dim value As FormStartPosition

value = instance.StartPosition

instance.StartPosition = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(FormStartPosition), L"CenterParent")]
virtual property FormStartPosition StartPosition {
	FormStartPosition get ();
	void set (FormStartPosition value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(FormStartPosition), "CenterParent")>]
abstract StartPosition : FormStartPosition with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(FormStartPosition), "CenterParent")>]
override StartPosition : FormStartPosition with get, set
```


#### Property Value
Type: FormStartPosition<br />The position of the dialog window when it first appears.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevColorDialog">DevColorDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />