# IWebDriverExtensions.IsAlertPresent Method 
 

Determines whether an alert modal dialog window is present in the current IWebDriver.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsAlertPresent(
	this IWebDriver drv
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsAlertPresent ( 
	drv As IWebDriver
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim drv As IWebDriver
Dim returnValue As Boolean

returnValue = drv.IsAlertPresent()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsAlertPresent(
	IWebDriver^ drv
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsAlertPresent : 
        drv : IWebDriver -> bool 

```


#### Parameters
&nbsp;<dl><dt>drv</dt><dd>Type: IWebDriver<br />The source IWebDriver.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the alert modal dialog window is present in the current IWebDriver, otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWebDriver. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples

**VB**<br />
``` VB
Using svc As FirefoxDriverService = FirefoxDriverService.CreateDefaultService(),
      drv As New FirefoxDriver(svc)

     drv.Navigate().GoToUrl("https://www.domain.com/")

     Dim isAlertPresent As Boolean = drv.isAlertPresent()
     Console.WriteLine($"{NameOf(isAlertPresent)}: {isAlertPresent}")
End Using
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions">IWebDriverExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver Namespace</a><br />