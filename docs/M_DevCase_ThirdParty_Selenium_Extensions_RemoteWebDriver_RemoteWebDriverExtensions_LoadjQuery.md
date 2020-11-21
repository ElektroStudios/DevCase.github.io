# RemoteWebDriverExtensions.LoadjQuery Method 
 

Loads jQuery from an external URL to the current page.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium_Extensions_RemoteWebDriver">DevCase.ThirdParty.Selenium.Extensions.RemoteWebDriver</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void LoadjQuery(
	this RemoteWebDriver drv,
	string version = "any",
	TimeSpan timeout = null
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub LoadjQuery ( 
	drv As RemoteWebDriver,
	Optional version As String = "any",
	Optional timeout As TimeSpan = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim drv As RemoteWebDriver
Dim version As String
Dim timeout As TimeSpan

drv.LoadjQuery(version, timeout)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void LoadjQuery(
	RemoteWebDriver^ drv, 
	String^ version = L"any", 
	TimeSpan timeout = nullptr
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member LoadjQuery : 
        drv : RemoteWebDriver * 
        ?version : string * 
        ?timeout : TimeSpan 
(* Defaults:
        let _version = defaultArg version "any"
        let _timeout = defaultArg timeout null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>drv</dt><dd>Type: RemoteWebDriver<br />The source IWebDriver.</dd><dt>version (Optional)</dt><dd>Type: System.String<br />The jQuery version. It must be the full version number matching one of the versions at <a href="https://code.jquery.com/jquery" target="_blank">https://code.jquery.com/jquery</a>. 

 The default value is: "any".</dd><dt>timeout (Optional)</dt><dd>Type: System.TimeSpan<br />The timeout value indicating how long to wait. Default value is 30 seconds.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type RemoteWebDriver. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_Extensions_RemoteWebDriver_RemoteWebDriverExtensions">RemoteWebDriverExtensions Class</a><br /><a href="N_DevCase_ThirdParty_Selenium_Extensions_RemoteWebDriver">DevCase.ThirdParty.Selenium.Extensions.RemoteWebDriver Namespace</a><br />