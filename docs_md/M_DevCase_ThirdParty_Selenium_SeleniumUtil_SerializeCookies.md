# SeleniumUtil.SerializeCookies Method (Cookie[], String)
 

Serializes the specified cookies to disk.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium">DevCase.ThirdParty.Selenium</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void SerializeCookies(
	Cookie[] cookies,
	string cookiesPath
)
```

**VB**<br />
``` VB
Public Shared Sub SerializeCookies ( 
	cookies As Cookie(),
	cookiesPath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim cookies As Cookie()
Dim cookiesPath As StringSeleniumUtil.SerializeCookies(cookies, cookiesPath)
```

**C++**<br />
``` C++
public:
static void SerializeCookies(
	array<Cookie^>^ cookies, 
	String^ cookiesPath
)
```

**F#**<br />
``` F#
static member SerializeCookies : 
        cookies : Cookie[] * 
        cookiesPath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>cookies</dt><dd>Type: Cookie[]<br />\[Missing <param name="cookies"/> documentation for "M:DevCase.ThirdParty.Selenium.SeleniumUtil.SerializeCookies(OpenQA.Selenium.Cookie[],System.String)"\]</dd><dt>cookiesPath</dt><dd>Type: System.String<br />The file path of the cookies container.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Using svc As FirefoxDriverService = FirefoxDriverService.CreateDefaultService(),
      drv As New FirefoxDriver(svc)

    drv.Navigate().GoToUrl("https://www.amazon.com/")
    Thread.Sleep(2000)

    Dim cookies As OpenQA.Selenium.Cookie() = drv.Manage.Cookies.AllCookies.ToArray()
    SeleniumUtil.SerializeCookies(cookies, "C:\cookies.bin")
End Using
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_SeleniumUtil">SeleniumUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_Selenium_SeleniumUtil_SerializeCookies">SerializeCookies Overload</a><br /><a href="N_DevCase_ThirdParty_Selenium">DevCase.ThirdParty.Selenium Namespace</a><br />