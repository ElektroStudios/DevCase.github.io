# WebUtil.DownloadWebpage Method (String, WebProxy, Encoding, KeyValuePair(String, String)[])
 

Downloads the source-code of an Url that points to an Html document.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string DownloadWebpage(
	string url,
	WebProxy proxy,
	Encoding enc,
	params KeyValuePair<string, string>[] additionalHeaders
)
```

**VB**<br />
``` VB
Public Shared Function DownloadWebpage ( 
	url As String,
	proxy As WebProxy,
	enc As Encoding,
	ParamArray additionalHeaders As KeyValuePair(Of String, String)()
) As String
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim proxy As WebProxy
Dim enc As Encoding
Dim additionalHeaders As KeyValuePair(Of String, String)()
Dim returnValue As String

returnValue = WebUtil.DownloadWebpage(url, 
	proxy, enc, additionalHeaders)
```

**C++**<br />
``` C++
public:
static String^ DownloadWebpage(
	String^ url, 
	WebProxy^ proxy, 
	Encoding^ enc, 
	... array<KeyValuePair<String^, String^>>^ additionalHeaders
)
```

**F#**<br />
``` F#
static member DownloadWebpage : 
        url : string * 
        proxy : WebProxy * 
        enc : Encoding * 
        additionalHeaders : KeyValuePair<string, string>[] -> string 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The Url address.</dd><dt>proxy</dt><dd>Type: System.Net.WebProxy<br />The proxy to use.</dd><dt>enc</dt><dd>Type: System.Text.Encoding<br />The Encoding used to read the webpage.</dd><dt>additionalHeaders</dt><dd>Type: System.Collections.Generic.KeyValuePair(String, String)[]<br />Specifies custom headers to perform the web request.</dd></dl>

#### Return Value
Type: String<br />The resulting source-code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim proxy As New WebProxy(Host:="myproxy address", Port:=800)
proxy.Credentials = New NetworkCredential("user", "pass")
Dim html As String = DownloadWebpage("http://www.elhacker.net/", proxy, Encoding.UTF8, New KeyValuePair(Of String, String)("user-agent", "Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.2; .NET CLR 1.0.3705;)"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadWebpage">DownloadWebpage Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />