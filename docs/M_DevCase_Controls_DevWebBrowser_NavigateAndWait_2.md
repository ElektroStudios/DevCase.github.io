# DevWebBrowser.NavigateAndWait Method (String, Boolean, CookieCollection)
 

Navigates to the specified url and waits the page to be loaded.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public void NavigateAndWait(
	string url,
	bool newWindow,
	CookieCollection cookies
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Sub NavigateAndWait ( 
	url As String,
	newWindow As Boolean,
	cookies As CookieCollection
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevWebBrowser
Dim url As String
Dim newWindow As Boolean
Dim cookies As CookieCollection

instance.NavigateAndWait(url, newWindow, 
	cookies)
```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
void NavigateAndWait(
	String^ url, 
	bool newWindow, 
	CookieCollection^ cookies
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
member NavigateAndWait : 
        url : string * 
        newWindow : bool * 
        cookies : CookieCollection -> unit 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to navigate.</dd><dt>newWindow</dt><dd>Type: System.Boolean<br />Indicates whether the url should be open into a new browser window.</dd><dt>cookies</dt><dd>Type: System.Net.CookieCollection<br />The cookies to set for the specified url.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevWebBrowser">DevWebBrowser Class</a><br /><a href="Overload_DevCase_Controls_DevWebBrowser_NavigateAndWait">NavigateAndWait Overload</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />