# HUDForm.Factory Property 
 

Gets the Factory instance that creates Direct2D resources.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public Factory Factory { get; }
```

**VB**<br />
``` VB
<BrowsableAttribute(true)>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public ReadOnly Property Factory As Factory
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As HUDForm
Dim value As Factory

value = instance.Factory

```

**C++**<br />
``` C++
public:
[BrowsableAttribute(true)]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
property Factory^ Factory {
	Factory^ get ();
}
```

**F#**<br />
``` F#
[<BrowsableAttribute(true)>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member Factory : Factory with get

```


#### Property Value
Type: Factory<br />The Factory instance that creates Direct2D resources.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_SharpDX_HUDForm">HUDForm Class</a><br /><a href="N_DevCase_ThirdParty_SharpDX">DevCase.ThirdParty.SharpDX Namespace</a><br />