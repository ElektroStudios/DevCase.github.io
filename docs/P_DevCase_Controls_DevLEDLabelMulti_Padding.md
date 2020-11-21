# DevLEDLabelMulti.Padding Property 
 

Gets or sets padding within the control.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(Padding), "4, 4, 4, 4")]
public virtual Padding Padding { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Padding), "4, 4, 4, 4")>
Public Overridable Property Padding As Padding
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLEDLabelMulti
Dim value As Padding

value = instance.Padding

instance.Padding = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(Padding), L"4, 4, 4, 4")]
virtual property Padding Padding {
	Padding get ();
	void set (Padding value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Padding), "4, 4, 4, 4")>]
abstract Padding : Padding with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(Padding), "4, 4, 4, 4")>]
override Padding : Padding with get, set
```


#### Property Value
Type: Padding<br />The padding within the control.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLEDLabelMulti">DevLEDLabelMulti Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />