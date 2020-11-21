# CaptchaGenerator.GridEnabled Property 
 

Gets or sets a value indicating whether grid drawing is enabled in the captcha image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool GridEnabled { get; set; }
```

**VB**<br />
``` VB
Public Property GridEnabled As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CaptchaGenerator
Dim value As Boolean

value = instance.GridEnabled

instance.GridEnabled = value
```

**C++**<br />
``` C++
public:
property bool GridEnabled {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member GridEnabled : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if grid drawing is enabled; `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_CaptchaGenerator">CaptchaGenerator Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />