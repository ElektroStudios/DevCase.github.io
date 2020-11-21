# IWebDriverExtensions Class
 

Contains custom extension methods to use with IWebDriver type.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.ThirdParty.Selenium.Extensions.IWebDriver.IWebDriverExtensions<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[HideModuleNameAttribute]
public sealed class IWebDriverExtensions
```

**VB**<br />
``` VB
<ExtensionAttribute>
<HideModuleNameAttribute>
Public NotInheritable Class IWebDriverExtensions
```

**VB Usage**<br />
``` VB Usage
Dim instance As IWebDriverExtensions
```

**C++**<br />
``` C++
[ExtensionAttribute]
[HideModuleNameAttribute]
public ref class IWebDriverExtensions sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ExtensionAttribute>]
[<HideModuleNameAttribute>]
type IWebDriverExtensions =  class end
```

The IWebDriverExtensions type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_CloseAlert">CloseAlert</a></td><td>
Instructs to close the current alert modal dialog window present in the current IWebDriver.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_FindElementsByPartialText_1">FindElementsByPartialText(IWebDriver, String, StringComparison)</a></td><td>
Finds a list of elements that match the partial text supplied.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_FindElementsByPartialText">FindElementsByPartialText(IWebDriver, By, String, StringComparison)</a></td><td>
Finds a list of elements using the given mechanism that match the partial text supplied.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_FindElementsByRegEx_1">FindElementsByRegEx(IWebDriver, Regex)</a></td><td>
Finds a list of elements that match the text supplied using RegEx.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_FindElementsByRegEx">FindElementsByRegEx(IWebDriver, By, Regex)</a></td><td>
Finds a list of elements using the given mechanism that match the text supplied using RegEx.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_FindElementsByText_1">FindElementsByText(IWebDriver, String, StringComparison)</a></td><td>
Finds a list of elements that match the text supplied.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_FindElementsByText">FindElementsByText(IWebDriver, By, String, StringComparison)</a></td><td>
Finds a list of elements using the given mechanism that match the text supplied.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_GetPlainText">GetPlainText</a></td><td>
Gets all the plain text in the current page.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_IsAlertPresent">IsAlertPresent</a></td><td>
Determines whether an alert modal dialog window is present in the current IWebDriver.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_IsElementPresent">IsElementPresent</a></td><td>
Determine whether an element is present in the current IWebDriver.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_RestoreCookies">RestoreCookies(IWebDriver, String)</a></td><td>
Restores a saved cookie container for the current browser session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_RestoreCookies_1">RestoreCookies(IWebDriver, String, String)</a></td><td>
Restores a saved cookie container for the specified domain in the browser session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_RestoreCookies_2">RestoreCookies(IWebDriver, String, Uri)</a></td><td>
Restores a saved cookie container for the specified domain in the browser session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_RestoreCookiesOfCurrentDomain">RestoreCookiesOfCurrentDomain</a></td><td>
Restores a saved cookie container for the current domain in the browser session.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_SaveCookies">SaveCookies(IWebDriver, String)</a></td><td>
Saves the current session cookies to disk.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_SaveCookies_1">SaveCookies(IWebDriver, String, String)</a></td><td>
Saves the current session cookies for the specified domain to disk.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_SaveCookies_2">SaveCookies(IWebDriver, String, Uri)</a></td><td>
Saves the current session cookies for the specified domain to disk.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_SaveCookiesOfCurrentDomain">SaveCookiesOfCurrentDomain</a></td><td>
Saves the current session cookies for the current domain to disk.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_WaitForPageToLoad">WaitForPageToLoad</a></td><td>
Waits for the current page to load.</td></tr></table>&nbsp;
<a href="#iwebdriverextensions-class">Back to Top</a>

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
<a href="#iwebdriverextensions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver Namespace</a><br />