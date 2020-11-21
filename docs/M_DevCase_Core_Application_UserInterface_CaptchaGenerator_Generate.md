# CaptchaGenerator.Generate Method 
 

Generates the <a href="T_DevCase_Core_Application_UserInterface_Captcha">Captcha</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Captcha Generate()
```

**VB**<br />
``` VB
Public Overridable Function Generate As Captcha
```

**VB Usage**<br />
``` VB Usage
Dim instance As CaptchaGenerator
Dim returnValue As Captcha

returnValue = instance.Generate()
```

**C++**<br />
``` C++
public:
virtual Captcha^ Generate()
```

**F#**<br />
``` F#
abstract Generate : unit -> Captcha 
override Generate : unit -> Captcha 
```


#### Return Value
Type: <a href="T_DevCase_Core_Application_UserInterface_Captcha">Captcha</a><br />A <a href="T_DevCase_Core_Application_UserInterface_Captcha">Captcha</a> instance that contains the resulting captcha image and text.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_CaptchaGenerator">CaptchaGenerator Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />