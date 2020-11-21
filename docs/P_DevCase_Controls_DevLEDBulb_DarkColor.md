# DevLEDBulb.DarkColor Property 
 

Gets the dark shade of the LED color used for gradient.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
public virtual Color DarkColor { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
Public Overridable ReadOnly Property DarkColor As Color
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevLEDBulb
Dim value As Color

value = instance.DarkColor

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
virtual property Color DarkColor {
	Color get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
abstract DarkColor : Color with get
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
override DarkColor : Color with get
```


#### Property Value
Type: Color<br />The dark shade of the LED color used for gradient.

## See Also


#### Reference
<a href="T_DevCase_Controls_DevLEDBulb">DevLEDBulb Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />