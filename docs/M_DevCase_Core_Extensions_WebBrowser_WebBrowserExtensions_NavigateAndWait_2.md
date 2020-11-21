# WebBrowserExtensions.NavigateAndWait Method (WebBrowser, Uri)
 

Navigates to the specified url and waits the page to be loaded.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_WebBrowser">DevCase.Core.Extensions.WebBrowser</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void NavigateAndWait(
	this WebBrowser sender,
	Uri uri
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub NavigateAndWait ( 
	sender As WebBrowser,
	uri As Uri
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As WebBrowser
Dim uri As Uri

sender.NavigateAndWait(uri)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void NavigateAndWait(
	WebBrowser^ sender, 
	Uri^ uri
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member NavigateAndWait : 
        sender : WebBrowser * 
        uri : Uri -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Windows.Forms.WebBrowser<br />The source WebBrowser.</dd><dt>uri</dt><dd>Type: System.Uri<br />The url to navigate.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type WebBrowser. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions">WebBrowserExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions_NavigateAndWait">NavigateAndWait Overload</a><br /><a href="N_DevCase_Core_Extensions_WebBrowser">DevCase.Core.Extensions.WebBrowser Namespace</a><br />