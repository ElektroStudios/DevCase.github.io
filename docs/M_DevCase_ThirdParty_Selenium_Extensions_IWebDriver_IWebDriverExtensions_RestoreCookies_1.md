# IWebDriverExtensions.RestoreCookies Method (IWebDriver, String, String)
 

Restores a saved cookie container for the specified domain in the browser session.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void RestoreCookies(
	this IWebDriver drv,
	string cookiesPath,
	string domain
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub RestoreCookies ( 
	drv As IWebDriver,
	cookiesPath As String,
	domain As String
)
```

**VB Usage**<br />
``` VB Usage
Dim drv As IWebDriver
Dim cookiesPath As String
Dim domain As String

drv.RestoreCookies(cookiesPath, domain)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void RestoreCookies(
	IWebDriver^ drv, 
	String^ cookiesPath, 
	String^ domain
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member RestoreCookies : 
        drv : IWebDriver * 
        cookiesPath : string * 
        domain : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>drv</dt><dd>Type: IWebDriver<br />The source IWebDriver.</dd><dt>cookiesPath</dt><dd>Type: System.String<br />The cookies file path.</dd><dt>domain</dt><dd>Type: System.String<br />The domain name.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWebDriver. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions">IWebDriverExtensions Class</a><br /><a href="Overload_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_RestoreCookies">RestoreCookies Overload</a><br /><a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver Namespace</a><br />