# IWebDriverExtensions.GetPlainText Method 
 

Gets all the plain text in the current page.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string GetPlainText(
	this IWebDriver drv
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetPlainText ( 
	drv As IWebDriver
) As String
```

**VB Usage**<br />
``` VB Usage
Dim drv As IWebDriver
Dim returnValue As String

returnValue = drv.GetPlainText()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ GetPlainText(
	IWebDriver^ drv
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetPlainText : 
        drv : IWebDriver -> string 

```


#### Parameters
&nbsp;<dl><dt>drv</dt><dd>Type: IWebDriver<br />The source IWebDriver.</dd></dl>

#### Return Value
Type: String<br />The plain text in the current page.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IWebDriver. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_Extensions_IWebDriver_IWebDriverExtensions">IWebDriverExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Selenium_Extensions_IWebDriver">DevCase.ThirdParty.Selenium.Extensions.IWebDriver Namespace</a><br />