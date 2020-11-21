# IWebDriverExtensions.IsElementPresent Method 
 

Determine whether an element is present in the current IWebDriver.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsElementPresent(
	this IWebDriver drv,
	By by
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsElementPresent ( 
	drv As IWebDriver,
	by As By
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim drv As IWebDriver
Dim by As By
Dim returnValue As Boolean

returnValue = drv.IsElementPresent(by)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsElementPresent(
	IWebDriver^ drv, 
	By^ by
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsElementPresent : 
        drv : IWebDriver * 
        by : By -> bool 

```


#### Parameters
&nbsp;<dl><dt>drv</dt><dd>Type: IWebDriver<br />The source IWebDriver.</dd><dt>by</dt><dd>Type: By<br />The locating mechanism to use to find the element.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the element is present in the current IWebDriver, otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWebDriver. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions">IWebDriverExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver Namespace</a><br />