# DevWebBrowser.MouseButtonMiddleEnabled Property 
 

Gets or sets a value indicating whether middle mouse button events are handled. 

 In case of you want to prevent the user from using middle mouse button to scroll the page, then set this property to `false` (`False` in Visual Basic).

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)]
[DefaultValueAttribute(typeof(bool), "True")]
public virtual bool MouseButtonMiddleEnabled { get; set; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>
<DefaultValueAttribute(GetType(Boolean), "True")>
Public Overridable Property MouseButtonMiddleEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevWebBrowser
Dim value As Boolean

value = instance.MouseButtonMiddleEnabled

instance.MouseButtonMiddleEnabled = value
```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
[DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility::Visible)]
[DefaultValueAttribute(typeof(bool), L"True")]
virtual property bool MouseButtonMiddleEnabled {
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
abstract MouseButtonMiddleEnabled : bool with get, set
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
[<DesignerSerializationVisibilityAttribute(DesignerSerializationVisibility.Visible)>]
[<DefaultValueAttribute(typeof(bool), "True")>]
override MouseButtonMiddleEnabled : bool with get, set
```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if middle mouse button events are handled; otherwise `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Controls_DevWebBrowser">DevWebBrowser Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />