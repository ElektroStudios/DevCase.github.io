# IBufferedControl.DoubleBuffered Property 
 

Gets or sets a value indicating whether this control should redraw its surface using a secondary buffer to reduce or prevent flicker.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(bool), "True")]
bool DoubleBuffered { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Boolean), "True")>
Property DoubleBuffered As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As IBufferedControl
Dim value As Boolean

value = instance.DoubleBuffered

instance.DoubleBuffered = value
```

**C++**<br />
``` C++
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(bool), L"True")]
property bool DoubleBuffered {
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
abstract DoubleBuffered : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the surface of the control should be drawn using double buffering; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Design_IBufferedControl">IBufferedControl Interface</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />