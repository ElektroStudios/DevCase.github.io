# SeleniumUtil Class
 

Contains Selenium related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.Selenium.SeleniumUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium">DevCase.ThirdParty.Selenium</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class SeleniumUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class SeleniumUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As SeleniumUtil
```

**C++**<br />
``` C++
public ref class SeleniumUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type SeleniumUtil =  
    class
        inherit AestheticObject
    end
```

The SeleniumUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_SeleniumUtil_DeserializeCookies">DeserializeCookies</a></td><td>
Deserializes a cookie container from disk, previously saved using <a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_SaveCookies">SaveCookies(IWebDriver, String)</a> or <a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_SaveCookiesOfCurrentDomain">SaveCookiesOfCurrentDomain(IWebDriver, String)</a> methods.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_SeleniumUtil_MicrosoftLiveMailRegister">MicrosoftLiveMailRegister</a></td><td>
Automate the specified web-browser to register a new mail account at 'https://signup.live.com/'. 

 Note that this function use random text (gathered from <a href="T_DevCase_Core_Text_Tools_StringUtil_WordLists">StringUtil.WordLists</a> class properties) to fill the registration form.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_SeleniumUtil_SerializeCookies">SerializeCookies(Cookie[], String)</a></td><td>
Serializes the specified cookies to disk.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_SeleniumUtil_SerializeCookies_1">SerializeCookies(ReadOnlyCollection(Cookie), String)</a></td><td>
Serializes the specified cookies to disk.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_SeleniumUtil_YandexMailRegister">YandexMailRegister</a></td><td>
Automate the specified web-browser to register a new mail account at 'https://yandex.com/'. 

 Note that this function use random text (gathered from <a href="T_DevCase_Core_Text_Tools_StringUtil_WordLists">StringUtil.WordLists</a> class properties) to fill the registration form.</td></tr></table>&nbsp;
<a href="#seleniumutil-class">Back to Top</a>

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
<a href="#seleniumutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Selenium">DevCase.ThirdParty.Selenium Namespace</a><br />