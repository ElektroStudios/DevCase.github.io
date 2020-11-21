# HUDForm.Render Property 
 

Gets the render that renders drawing instructions to this <a href="T_DevCase_ThirdParty_SharpDX_HUDForm">HUDForm</a> window.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public WindowRenderTarget Render { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public ReadOnly Property Render As WindowRenderTarget
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As HUDForm
Dim value As WindowRenderTarget

value = instance.Render

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
property WindowRenderTarget^ Render {
	WindowRenderTarget^ get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member Render : WindowRenderTarget with get

```


#### Property Value
Type: WindowRenderTarget<br />The render that renders drawing instructions to this <a href="T_DevCase_ThirdParty_SharpDX_HUDForm">HUDForm</a> window.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SharpDX_HUDForm">HUDForm Class</a><br /><a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX Namespace</a><br />