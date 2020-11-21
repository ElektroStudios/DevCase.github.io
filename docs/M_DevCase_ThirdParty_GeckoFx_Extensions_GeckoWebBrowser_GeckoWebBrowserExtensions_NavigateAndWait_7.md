# GeckoWebBrowserExtensions.NavigateAndWait Method (GeckoWebBrowser, Uri, GeckoLoadFlags, String, MimeInputStream, MimeInputStream)
 

Navigates to the specified url and waits the page to be loaded.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx_Extensions_GeckoWebBrowser">DevCase.ThirdParty.GeckoFx.Extensions.GeckoWebBrowser</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void NavigateAndWait(
	this GeckoWebBrowser sender,
	Uri uri,
	GeckoLoadFlags loadflags,
	string referrer,
	MimeInputStream postData,
	MimeInputStream headers
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub NavigateAndWait ( 
	sender As GeckoWebBrowser,
	uri As Uri,
	loadflags As GeckoLoadFlags,
	referrer As String,
	postData As MimeInputStream,
	headers As MimeInputStream
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As GeckoWebBrowser
Dim uri As Uri
Dim loadflags As GeckoLoadFlags
Dim referrer As String
Dim postData As MimeInputStream
Dim headers As MimeInputStream

sender.NavigateAndWait(uri, loadflags, 
	referrer, postData, headers)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void NavigateAndWait(
	GeckoWebBrowser^ sender, 
	Uri^ uri, 
	GeckoLoadFlags loadflags, 
	String^ referrer, 
	MimeInputStream^ postData, 
	MimeInputStream^ headers
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member NavigateAndWait : 
        sender : GeckoWebBrowser * 
        uri : Uri * 
        loadflags : GeckoLoadFlags * 
        referrer : string * 
        postData : MimeInputStream * 
        headers : MimeInputStream -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: GeckoWebBrowser<br />The source GeckoWebBrowser.</dd><dt>uri</dt><dd>Type: System.Uri<br />The url to navigate.</dd><dt>loadflags</dt><dd>Type: GeckoLoadFlags<br />Flags which specify how the page is loaded.</dd><dt>referrer</dt><dd>Type: System.String<br />The referring Uurl.</dd><dt>postData</dt><dd>Type: MimeInputStream<br />The post data.</dd><dt>headers</dt><dd>Type: MimeInputStream<br />The headers.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type GeckoWebBrowser. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_GeckoFx_Extensions_GeckoWebBrowser_GeckoWebBrowserExtensions">GeckoWebBrowserExtensions Class</a><br /><a href="Overload_DevCase_ThirdParty_GeckoFx_Extensions_GeckoWebBrowser_GeckoWebBrowserExtensions_NavigateAndWait">NavigateAndWait Overload</a><br /><a href="N_DevCase_ThirdParty_GeckoFx_Extensions_GeckoWebBrowser">DevCase.ThirdParty.GeckoFx.Extensions.GeckoWebBrowser Namespace</a><br />