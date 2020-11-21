# DevStarRate.StarCount Property 
 

Gets or sets the amount of stars to display.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(int), "5")]
public virtual int StarCount { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Integer), "5")>
Public Overridable Property StarCount As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevStarRate
Dim value As Integer

value = instance.StarCount

instance.StarCount = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(int), L"5")]
virtual property int StarCount {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(int), "5")>]
abstract StarCount : int with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(int), "5")>]
override StarCount : int with get, set
```


#### Property Value
Type: Int32<br />The amount of stars to display.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevStarRate">DevStarRate Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />