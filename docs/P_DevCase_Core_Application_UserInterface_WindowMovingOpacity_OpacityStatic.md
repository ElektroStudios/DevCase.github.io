# WindowMovingOpacity.OpacityStatic Property 
 

Gets or sets the opacity to apply to the window when the window isn't moving, in a static position. 

 The valid range is from `0` to `100`.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual int OpacityStatic { get; set; }
```

**VB**<br />
``` VB
Public Overridable Property OpacityStatic As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowMovingOpacity
Dim value As Integer

value = instance.OpacityStatic

instance.OpacityStatic = value
```

**C++**<br />
``` C++
public:
virtual property int OpacityStatic {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
abstract OpacityStatic : int with get, set
override OpacityStatic : int with get, set
```


#### Property Value
Type: Int32<br />The opacity, from `0` to `100`.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_WindowMovingOpacity">WindowMovingOpacity Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />