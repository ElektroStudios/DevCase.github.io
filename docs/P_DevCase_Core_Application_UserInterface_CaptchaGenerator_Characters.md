# CaptchaGenerator.Characters Property 
 

Gets or sets the character set to build the captcha text.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public char[] Characters { get; set; }
```

**VB**<br />
``` VB
Public Property Characters As Char()
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CaptchaGenerator
Dim value As Char()

value = instance.Characters

instance.Characters = value
```

**C++**<br />
``` C++
public:
property array<wchar_t>^ Characters {
	array<wchar_t>^ get ();
	void set (array<wchar_t>^ value);
}
```

**F#**<br />
``` F#
member Characters : char[] with get, set

```


#### Property Value
Type: Char[]<br />The character set to build the captcha text.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_CaptchaGenerator">CaptchaGenerator Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />