# RemoteWebDriverExtensions.JQueryLoaded Method 
 

Determine whether jQuery is loaded in the current page.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_RemoteWebDriver">DevCase.ThirdParty.Selenium.Extensions.RemoteWebDriver</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool JQueryLoaded(
	this RemoteWebDriver drv
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function JQueryLoaded ( 
	drv As RemoteWebDriver
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim drv As RemoteWebDriver
Dim returnValue As Boolean

returnValue = drv.JQueryLoaded()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool JQueryLoaded(
	RemoteWebDriver^ drv
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member JQueryLoaded : 
        drv : RemoteWebDriver -> bool 

```


#### Parameters
&nbsp;<dl><dt>drv</dt><dd>Type: RemoteWebDriver<br />The source IWebDriver.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if jQuery is loaded in the current page; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RemoteWebDriver. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_Extensions_RemoteWebDriver_RemoteWebDriverExtensions">RemoteWebDriverExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Selenium_Extensions_RemoteWebDriver">DevCase.ThirdParty.Selenium.Extensions.RemoteWebDriver Namespace</a><br />