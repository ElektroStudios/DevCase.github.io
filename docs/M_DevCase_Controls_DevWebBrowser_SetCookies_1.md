# DevWebBrowser.SetCookies Method (String, Boolean, CookieCollection)
 

Sets one or more cookies for the specified URL.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void SetCookies(
	string url,
	bool persistent,
	CookieCollection cookies
)
```

**VB**<br />
``` VB
Public Sub SetCookies ( 
	url As String,
	persistent As Boolean,
	cookies As CookieCollection
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevWebBrowser
Dim url As String
Dim persistent As Boolean
Dim cookies As CookieCollection

instance.SetCookies(url, persistent, cookies)
```

**C++**<br />
``` C++
public:
void SetCookies(
	String^ url, 
	bool persistent, 
	CookieCollection^ cookies
)
```

**F#**<br />
``` F#
member SetCookies : 
        url : string * 
        persistent : bool * 
        cookies : CookieCollection -> unit 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The URL.</dd><dt>persistent</dt><dd>Type: System.Boolean<br />A value that indicates the cookie persistance. 

 If set to `true` (`True` in Visual Basic) (persistent), the cookie is set in the operating system cache. 

 If set to `false` (`False` in Visual Basic) (non-persistent), the cookie is only set for the life-time of the current process.</dd><dt>cookies</dt><dd>Type: System.Net.CookieCollection<br />The cookies to set.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevWebBrowser">DevWebBrowser Class</a><br /><a href="Overload_DevCase_Controls_DevWebBrowser_SetCookies">SetCookies Overload</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />