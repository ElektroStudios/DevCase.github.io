# DevLEDBulb.Activated Property 
 

Gets or sets a value indicating whether the LED light is turned On or Off.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(bool), "True")]
public virtual bool Activated { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Boolean), "True")>
Public Overridable Property Activated As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLEDBulb
Dim value As Boolean

value = instance.Activated

instance.Activated = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(bool), L"True")]
virtual property bool Activated {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(bool), "True")>]
abstract Activated : bool with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(bool), "True")>]
override Activated : bool with get, set
```


#### Property Value
Type: Boolean<br />A value indicating whether the LED light is turned On or Off.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLEDBulb">DevLEDBulb Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />