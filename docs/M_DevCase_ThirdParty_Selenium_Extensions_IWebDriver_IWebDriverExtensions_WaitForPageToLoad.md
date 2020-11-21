# IWebDriverExtensions.WaitForPageToLoad Method 
 

Waits for the current page to load.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void WaitForPageToLoad(
	this IWebDriver drv,
	TimeSpan timeout = null
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub WaitForPageToLoad ( 
	drv As IWebDriver,
	Optional timeout As TimeSpan = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim drv As IWebDriver
Dim timeout As TimeSpan

drv.WaitForPageToLoad(timeout)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void WaitForPageToLoad(
	IWebDriver^ drv, 
	TimeSpan timeout = nullptr
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member WaitForPageToLoad : 
        drv : IWebDriver * 
        ?timeout : TimeSpan 
(* Defaults:
        let _timeout = defaultArg timeout null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>drv</dt><dd>Type: IWebDriver<br />The source IWebDriver.</dd><dt>timeout (Optional)</dt><dd>Type: System.TimeSpan<br />The timeout value indicating how long to wait. Default value is 30 seconds.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWebDriver. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions">IWebDriverExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver Namespace</a><br />