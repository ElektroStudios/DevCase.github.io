# WebUtil.DownloadWebpage Method (String, WebProxy, String)
 

Downloads the source-code of an Url that points to an Html document.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string DownloadWebpage(
	string url,
	WebProxy proxy,
	string userAgent
)
```

**VB**<br />
``` VB
Public Shared Function DownloadWebpage ( 
	url As String,
	proxy As WebProxy,
	userAgent As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim proxy As WebProxy
Dim userAgent As String
Dim returnValue As String

returnValue = WebUtil.DownloadWebpage(url, 
	proxy, userAgent)
```

**C++**<br />
``` C++
public:
static String^ DownloadWebpage(
	String^ url, 
	WebProxy^ proxy, 
	String^ userAgent
)
```

**F#**<br />
``` F#
static member DownloadWebpage : 
        url : string * 
        proxy : WebProxy * 
        userAgent : string -> string 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The Url address.</dd><dt>proxy</dt><dd>Type: System.Net.WebProxy<br />The proxy to use.</dd><dt>userAgent</dt><dd>Type: System.String<br />Specifies a custom user-agent to perform the web request.</dd></dl>

#### Return Value
Type: String<br />The resulting source-code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim proxy As New WebProxy(Host:="myproxy address", Port:=800)
proxy.Credentials = New NetworkCredential("user", "pass")
Dim html As String = DownloadWebpage("http://www.elhacker.net/", proxy, "Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.2; .NET CLR 1.0.3705;)")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadWebpage">DownloadWebpage Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />