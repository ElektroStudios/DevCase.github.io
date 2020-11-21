# DevLEDLabelMulti.LEDCount Property 
 

Gets or sets the amount of <a href="T_DevCase_Controls_DevLEDLabel">DevLEDLabel</a> controls that are currently displayed.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(int), "4")]
public virtual int LEDCount { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Integer), "4")>
Public Overridable Property LEDCount As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLEDLabelMulti
Dim value As Integer

value = instance.LEDCount

instance.LEDCount = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(int), L"4")]
virtual property int LEDCount {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(int), "4")>]
abstract LEDCount : int with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(int), "4")>]
override LEDCount : int with get, set
```


#### Property Value
Type: Int32<br />The amount of <a href="T_DevCase_Controls_DevLEDLabel">DevLEDLabel</a> controls that are currently displayed.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLEDLabelMulti">DevLEDLabelMulti Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />