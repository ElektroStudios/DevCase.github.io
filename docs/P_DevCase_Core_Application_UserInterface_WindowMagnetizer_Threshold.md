# WindowMagnetizer.Threshold Property 
 

Gets or sets, in pixels, the minimum threshold that the magnetic window needs to dock it on the nearest window border. 

 (Default value is `20`))

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual int Threshold { get; set; }
```

**VB**<br />
``` VB
Public Overridable Property Threshold As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowMagnetizer
Dim value As Integer

value = instance.Threshold

instance.Threshold = value
```

**C++**<br />
``` C++
public:
virtual property int Threshold {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
abstract Threshold : int with get, set
override Threshold : int with get, set
```


#### Property Value
Type: Int32<br />The minimum threshold that the magnetic window needs to dock it on the nearest window border.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_WindowMagnetizer">WindowMagnetizer Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />