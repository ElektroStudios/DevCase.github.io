# IWebElementExtensions.AsRemoteWebElement Method 
 

Casts the source IWebElement to RemoteWebElement.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebElement">DevCase.ThirdParty.Selenium.Extensions.IWebElement</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static RemoteWebElement AsRemoteWebElement(
	this IWebElement element
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function AsRemoteWebElement ( 
	element As IWebElement
) As RemoteWebElement
```

**VB Usage**<br />
``` VB Usage
Dim element As IWebElement
Dim returnValue As RemoteWebElement

returnValue = element.AsRemoteWebElement()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static RemoteWebElement^ AsRemoteWebElement(
	IWebElement^ element
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AsRemoteWebElement : 
        element : IWebElement -> RemoteWebElement 

```


#### Parameters
&nbsp;<dl><dt>element</dt><dd>Type: IWebElement<br />An IWebElement that represents the element to cast.</dd></dl>

#### Return Value
Type: RemoteWebElement<br />The resulting RemoteWebElement.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWebElement. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples

**VB**<br />
``` VB
Using svc As FirefoxDriverService = FirefoxDriverService.CreateDefaultService(),
      drv As New FirefoxDriver(svc)

     drv.Navigate().GoToUrl("https://www.domain.com/")

     Dim element As RemoteWebElement = drv.FindElement(By.Id("name")).AsRemoteWebElement()
End Using
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_Extensions_IWebElement_IWebElementExtensions">IWebElementExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebElement">DevCase.ThirdParty.Selenium.Extensions.IWebElement Namespace</a><br />