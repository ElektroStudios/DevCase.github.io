# IWebDriverExtensions.FindElementsByText Method (IWebDriver, By, String, StringComparison)
 

Finds a list of elements using the given mechanism that match the text supplied.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static ReadOnlyCollection<IWebElement> FindElementsByText(
	this IWebDriver drv,
	By by,
	string text,
	StringComparison stringComparison
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function FindElementsByText ( 
	drv As IWebDriver,
	by As By,
	text As String,
	stringComparison As StringComparison
) As ReadOnlyCollection(Of IWebElement)
```

**VB Usage**<br />
``` VB Usage
Dim drv As IWebDriver
Dim by As By
Dim text As String
Dim stringComparison As StringComparison
Dim returnValue As ReadOnlyCollection(Of IWebElement)

returnValue = drv.FindElementsByText(by, 
	text, stringComparison)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static ReadOnlyCollection<IWebElement^>^ FindElementsByText(
	IWebDriver^ drv, 
	By^ by, 
	String^ text, 
	StringComparison stringComparison
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member FindElementsByText : 
        drv : IWebDriver * 
        by : By * 
        text : string * 
        stringComparison : StringComparison -> ReadOnlyCollection<IWebElement> 

```


#### Parameters
&nbsp;<dl><dt>drv</dt><dd>Type: IWebDriver<br />The source IWebDriver.</dd><dt>by</dt><dd>Type: By<br />The locating mechanism to use to find the element.</dd><dt>text</dt><dd>Type: System.String<br />The text to match in the element.</dd><dt>stringComparison</dt><dd>Type: System.StringComparison<br />Specifies the culture, case, and sort rules to be used.</dd></dl>

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

     Dim elements As ReadOnlyCollection(Of IWebElement) = 
         drv.FindElementsByText(By.ClassName("Button"), "text", StringComparison.OrdinalIgnoreCase)

     For Each element As IWebElement In elements
         Console.WriteLine($"({element.Location.ToString()}) '{element.TagName}' Text: {element.Text}")
     Loop

End Using
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions">IWebDriverExtensions Class</a><br /><a href="Overload_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions_FindElementsByText">FindElementsByText Overload</a><br /><a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver Namespace</a><br />