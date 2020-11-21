# NineKwCaptchaHelper.SolveCaptchaAsync Method 
 

Asynchronouslly Solves the specified captcha image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_NineKwCaptcha">DevCase.ThirdParty.NineKwCaptcha</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<string> SolveCaptchaAsync(
	string imagePath,
	int timeout = 120000
)
```

**VB**<br />
``` VB
Public Function SolveCaptchaAsync ( 
	imagePath As String,
	Optional timeout As Integer = 120000
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim instance As NineKwCaptchaHelper
Dim imagePath As String
Dim timeout As Integer
Dim returnValue As Task(Of String)

returnValue = instance.SolveCaptchaAsync(imagePath, 
	timeout)
```

**C++**<br />
``` C++
public:
Task<String^>^ SolveCaptchaAsync(
	String^ imagePath, 
	int timeout = 120000
)
```

**F#**<br />
``` F#
member SolveCaptchaAsync : 
        imagePath : string * 
        ?timeout : int 
(* Defaults:
        let _timeout = defaultArg timeout 120000
*)
-> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>imagePath</dt><dd>Type: System.String<br />The image path.</dd><dt>timeout (Optional)</dt><dd>Type: System.Int32<br />The maximum timeout, in milliseconds, to wait for a captcha to be solved. 

 The function returns if the timeout interval is exceed. Default value is 120000 (2 minutes).</dd></dl>

#### Return Value
Type: Task(String)<br />The solved captcha text.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_NineKwCaptcha_NineKwCaptchaHelper">NineKwCaptchaHelper Class</a><br /><a href="N_DevCase_ThirdParty_NineKwCaptcha">DevCase.ThirdParty.NineKwCaptcha Namespace</a><br />