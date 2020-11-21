# DevLabel.ShowStroke Property 
 

Gets or sets a value indicating whether a stroke is shown around the text of the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(bool), "False")]
public virtual bool ShowStroke { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Boolean), "False")>
Public Overridable Property ShowStroke As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLabel
Dim value As Boolean

value = instance.ShowStroke

instance.ShowStroke = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(bool), L"False")]
virtual property bool ShowStroke {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(bool), "False")>]
abstract ShowStroke : bool with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(bool), "False")>]
override ShowStroke : bool with get, set
```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the stroke is shown around; otherwise `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLabel">DevLabel Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />