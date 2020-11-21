# DevLEDLabelMulti.DecimalOn Property 
 

Gets or sets a value indicating whether the decimal point LED is turned on.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(bool), "False")]
public override bool DecimalOn { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Boolean), "False")>
Public Overrides Property DecimalOn As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLEDLabelMulti
Dim value As Boolean

value = instance.DecimalOn

instance.DecimalOn = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(bool), L"False")]
virtual property bool DecimalOn {
	bool get () override;
	void set (bool value) override;
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(bool), "False")>]
abstract DecimalOn : bool with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(bool), "False")>]
override DecimalOn : bool with get, set
```


#### Property Value
Type: Boolean<br />A value indicating whether the decimal point LED is turned on.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLEDLabelMulti">DevLEDLabelMulti Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />