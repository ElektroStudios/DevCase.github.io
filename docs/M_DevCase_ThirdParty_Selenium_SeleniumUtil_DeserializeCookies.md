# SeleniumUtil.DeserializeCookies Method 
 

Deserializes a cookie container from disk, previously saved using <a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_SaveCookies">SaveCookies(IWebDriver, String)</a> or <a href="M_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_SaveCookiesOfCurrentDomain">SaveCookiesOfCurrentDomain(IWebDriver, String)</a> methods.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium">DevCase.ThirdParty.Selenium</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<Cookie> DeserializeCookies(
	string cookiesPath
)
```

**VB**<br />
``` VB
Public Shared Function DeserializeCookies ( 
	cookiesPath As String
) As ReadOnlyCollection(Of Cookie)
```

**VB Usage**<br />
``` VB Usage
Dim cookiesPath As String
Dim returnValue As ReadOnlyCollection(Of Cookie)

returnValue = SeleniumUtil.DeserializeCookies(cookiesPath)
```

**C++**<br />
``` C++
public:
static ReadOnlyCollection<Cookie^>^ DeserializeCookies(
	String^ cookiesPath
)
```

**F#**<br />
``` F#
static member DeserializeCookies : 
        cookiesPath : string -> ReadOnlyCollection<Cookie> 

```


#### Parameters
&nbsp;<dl><dt>cookiesPath</dt><dd>Type: System.String<br />The file path of the cookies container.</dd></dl>

#### Return Value
Type: ReadOnlyCollection(Cookie)<br />A ReadOnlyCollection(T) object with the cookies.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim cookies As ReadOnlyCollection(Of OpenQA.Selenium.Cookie) = SeleniumUtil.DeserializeCookies("C:\cookies.bin")

For Each cookie As OpenQA.Selenium.Cookie In cookies
    Console.WriteLine(cookie.ToString())
Next cookie
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_SeleniumUtil">SeleniumUtil Class</a><br /><a href="N_DevCase_ThirdParty_Selenium">DevCase.ThirdParty.Selenium Namespace</a><br />