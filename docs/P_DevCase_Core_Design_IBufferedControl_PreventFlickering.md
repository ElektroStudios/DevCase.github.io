# IBufferedControl.PreventFlickering Property 
 

Gets or sets a value that indicates whether the control should avoid unwanted flickering effects. 

 If `true` (`True` in Visual Basic), this will avoid any flickering effect on the control, however, it will also have a negative impact by slowing down the responsiveness of the control about to 30% slower. 

 This negative impact doesn't affect to the performance of the application itself, just to the performance of this control.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(bool), "False")]
bool PreventFlickering { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Boolean), "False")>
Property PreventFlickering As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As IBufferedControl
Dim value As Boolean

value = instance.PreventFlickering

instance.PreventFlickering = value
```

**C++**<br />
``` C++
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(bool), L"False")]
property bool PreventFlickering {
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
abstract PreventFlickering : bool with get, set

```


#### Property Value
Type: Boolean<br />A value that indicates whether the control should avoid unwanted flickering effects.

## See Also


#### Reference
<a href="T_DevCase_Core_Design_IBufferedControl">IBufferedControl Interface</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />