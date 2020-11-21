# DevStarRate.Value Property 
 

Gets or sets the star rating value.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(int), "0")]
public int Value { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Integer), "0")>
Public Property Value As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevStarRate
Dim value As Integer

value = instance.Value

instance.Value = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(int), L"0")]
property int Value {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(int), "0")>]
member Value : int with get, set

```


#### Property Value
Type: Int32<br />The star rating value.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevStarRate">DevStarRate Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />