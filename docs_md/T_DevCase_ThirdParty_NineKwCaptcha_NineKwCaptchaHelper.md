# NineKwCaptchaHelper Class
 

9KW Captcha service wrapper.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.NineKwCaptcha.NineKwCaptchaHelper<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_NineKwCaptcha">DevCase.ThirdParty.NineKwCaptcha</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class NineKwCaptchaHelper : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class NineKwCaptchaHelper
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As NineKwCaptchaHelper
```

**C++**<br />
``` C++
public ref class NineKwCaptchaHelper sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type NineKwCaptchaHelper =  
    class
        inherit AestheticObject
    end
```

The NineKwCaptchaHelper type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_NineKwCaptcha_NineKwCaptchaHelper__ctor">NineKwCaptchaHelper</a></td><td>
Initializes a new instance of the NineKwCaptchaHelper class.</td></tr></table>&nbsp;
<a href="#ninekwcaptchahelper-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_NineKwCaptcha_NineKwCaptchaHelper_ApiKey">ApiKey</a></td><td>
Gets the 9KW's API user key.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_NineKwCaptcha_NineKwCaptchaHelper_Credits">Credits</a></td><td>
Gets the remaining credits for the current account.</td></tr></table>&nbsp;
<a href="#ninekwcaptchahelper-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_NineKwCaptcha_NineKwCaptchaHelper_SolveCaptcha">SolveCaptcha</a></td><td>
Solves the specified captcha image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_NineKwCaptcha_NineKwCaptchaHelper_SolveCaptchaAsync">SolveCaptchaAsync</a></td><td>
Asynchronouslly Solves the specified captcha image.</td></tr></table>&nbsp;
<a href="#ninekwcaptchahelper-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#ninekwcaptchahelper-class">Back to Top</a>

## Remarks
Visit <a href="http://9kw.eu/" target="_blank">http://9kw.eu/</a> for further info.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim captchaSolver As New NineKWCaptchaHelper(apiKey:="XXXXXXXXXXXXXXXXXXX")
Dim imagePath As String = "C:\captcha.png"
Dim result As String = String.Empty

Console.WriteLine(String.Format("User Credits: {0}", captchaSolver.GetCredits()))
Console.WriteLine(String.Format("Captcha Img.: {0}", imagePath))

Console.WriteLine("Solving Captcha, please wait...")
result = captchaSolver.SolveCaptcha(imagePath)
Console.WriteLine(String.Format("Result: {0}", result))

Console.ReadKey()
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_NineKwCaptcha">DevCase.ThirdParty.NineKwCaptcha Namespace</a><br />