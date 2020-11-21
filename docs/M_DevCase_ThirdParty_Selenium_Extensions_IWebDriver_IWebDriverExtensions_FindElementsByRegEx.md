# IWebDriverExtensions.FindElementsByRegEx Method (IWebDriver, By, Regex)
 

Finds a list of elements using the given mechanism that match the text supplied using RegEx.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static ReadOnlyCollection<IWebElement> FindElementsByRegEx(
	this IWebDriver drv,
	By by,
	Regex regEx
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function FindElementsByRegEx ( 
	drv As IWebDriver,
	by As By,
	regEx As Regex
) As ReadOnlyCollection(Of IWebElement)
```

**VB Usage**<br />
``` VB Usage
Dim drv As IWebDriver
Dim by As By
Dim regEx As Regex
Dim returnValue As ReadOnlyCollection(Of IWebElement)

returnValue = drv.FindElementsByRegEx(by, 
	regEx)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static ReadOnlyCollection<IWebElement^>^ FindElementsByRegEx(
	IWebDriver^ drv, 
	By^ by, 
	Regex^ regEx
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member FindElementsByRegEx : 
        drv : IWebDriver * 
        by : By * 
        regEx : Regex -> ReadOnlyCollection<IWebElement> 

```


#### Parameters
&nbsp;<dl><dt>drv</dt><dd>Type: IWebDriver<br />The source IWebDriver.</dd><dt>by</dt><dd>Type: By<br />The locating mechanism to use to find the element.</dd><dt>regEx</dt><dd>Type: System.Text.RegularExpressions.Regex<br />The Regular Expression used to match the element text.</dd></dl>

#### Return Value
Type: ReadOnlyCollection(IWebElement)<br />ReadOnlyCollection(T) of Elements that match the object so that you can interact that object.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWebDriver. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples

**VB**<br />
``` VB
Using svc As FirefoxDriverService = FirefoxDriverService.CreateDefaultService(),
      drv As New FirefoxDriver(svc)

     drv.Navigate().GoToUrl("https://www.domain.com/")

     Dim regEx As New Regex("pattern", RegexOptions.IgnoreCase)

     Dim elements As ReadOnlyCollection(Of IWebElement) = 
         drv.FindElementsByRegEx(By.ClassName("Button"), regEx)

     For Each element As IWebElement In elements
         Console.WriteLine($"({element.Location.ToString()}) '{element.TagName}' Text: {element.Text}")
     Loop

End Using
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions">IWebDriverExtensions Class</a><br /><a href="Overload_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_FindElementsByRegEx">FindElementsByRegEx Overload</a><br /><a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver Namespace</a><br />