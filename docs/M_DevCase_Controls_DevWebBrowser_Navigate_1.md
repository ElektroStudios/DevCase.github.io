# DevWebBrowser.Navigate Method (String, CookieCollection)
 

Navigates to the specified url.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public void Navigate(
	string url,
	CookieCollection cookies
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Sub Navigate ( 
	url As String,
	cookies As CookieCollection
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevWebBrowser
Dim url As String
Dim cookies As CookieCollection

instance.Navigate(url, cookies)
```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
void Navigate(
	String^ url, 
	CookieCollection^ cookies
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member Navigate : 
        url : string * 
        cookies : CookieCollection -> unit 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to navigate.</dd><dt>cookies</dt><dd>Type: System.Net.CookieCollection<br />The cookies to set for the specified url.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevWebBrowser">DevWebBrowser Class</a><br /><a href="Overload_DevCase_Controls_DevWebBrowser_Navigate">Navigate Overload</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />