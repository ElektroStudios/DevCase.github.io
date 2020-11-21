# GeckoWebBrowserExtensions.NavigateAndWait Method (GeckoWebBrowser, String)
 

Navigates to the specified url and waits the page to be loaded.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx_Extensions_GeckoWebBrowser">DevCase.ThirdParty.GeckoFx.Extensions.GeckoWebBrowser</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void NavigateAndWait(
	this GeckoWebBrowser sender,
	string url
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub NavigateAndWait ( 
	sender As GeckoWebBrowser,
	url As String
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As GeckoWebBrowser
Dim url As String

sender.NavigateAndWait(url)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void NavigateAndWait(
	GeckoWebBrowser^ sender, 
	String^ url
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member NavigateAndWait : 
        sender : GeckoWebBrowser * 
        url : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: GeckoWebBrowser<br />The source GeckoWebBrowser.</dd><dt>url</dt><dd>Type: System.String<br />The url to navigate.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type GeckoWebBrowser. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_Extensions_GeckoWebBrowser_GeckoWebBrowserExtensions">GeckoWebBrowserExtensions Class</a><br /><a href="Overload_DevCase_ThirdParty_GeckoFx_Extensions_GeckoWebBrowser_GeckoWebBrowserExtensions_NavigateAndWait">NavigateAndWait Overload</a><br /><a href="N_DevCase_ThirdParty_GeckoFx_Extensions_GeckoWebBrowser">DevCase.ThirdParty.GeckoFx.Extensions.GeckoWebBrowser Namespace</a><br />