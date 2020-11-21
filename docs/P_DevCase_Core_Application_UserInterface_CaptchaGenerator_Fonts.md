# CaptchaGenerator.Fonts Property 
 

Gets or sets the fonts to use in the captcha generation.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FontFamily[] Fonts { get; set; }
```

**VB**<br />
``` VB
Public Property Fonts As FontFamily()
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CaptchaGenerator
Dim value As FontFamily()

value = instance.Fonts

instance.Fonts = value
```

**C++**<br />
``` C++
public:
property array<FontFamily^>^ Fonts {
	array<FontFamily^>^ get ();
	void set (array<FontFamily^>^ value);
}
```

**F#**<br />
``` F#
member Fonts : FontFamily[] with get, set

```


#### Property Value
Type: FontFamily[]<br />The fonts to use in the captcha generation.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_CaptchaGenerator">CaptchaGenerator Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />