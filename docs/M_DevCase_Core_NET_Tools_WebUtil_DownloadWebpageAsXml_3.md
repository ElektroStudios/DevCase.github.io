# WebUtil.DownloadWebpageAsXml Method (String, WebProxy, KeyValuePair(String, String)[])
 

Downloads the source-code of an Url that points to an Html document, then transforms it to Xml.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static XDocument DownloadWebpageAsXml(
	string url,
	WebProxy proxy,
	params KeyValuePair<string, string>[] additionalHeaders
)
```

**VB**<br />
``` VB
Public Shared Function DownloadWebpageAsXml ( 
	url As String,
	proxy As WebProxy,
	ParamArray additionalHeaders As KeyValuePair(Of String, String)()
) As XDocument
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim proxy As WebProxy
Dim additionalHeaders As KeyValuePair(Of String, String)()
Dim returnValue As XDocument

returnValue = WebUtil.DownloadWebpageAsXml(url, 
	proxy, additionalHeaders)
```

**C++**<br />
``` C++
public:
static XDocument^ DownloadWebpageAsXml(
	String^ url, 
	WebProxy^ proxy, 
	... array<KeyValuePair<String^, String^>>^ additionalHeaders
)
```

**F#**<br />
``` F#
static member DownloadWebpageAsXml : 
        url : string * 
        proxy : WebProxy * 
        additionalHeaders : KeyValuePair<string, string>[] -> XDocument 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The Url address.</dd><dt>proxy</dt><dd>Type: System.Net.WebProxy<br />The proxy to use.</dd><dt>additionalHeaders</dt><dd>Type: System.Collections.Generic.KeyValuePair(String, String)[]<br />Specifies custom headers to perform the web request.</dd></dl>

#### Return Value
Type: XDocument<br />The resulting source-code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim proxy As New WebProxy(Host:="myproxy address", Port:=800)
proxy.Credentials = New NetworkCredential("user", "pass")
Dim xml As XDocument = DownloadWebpageAsXml("http://www.elhacker.net/", proxy, New KeyValuePair(Of String, String)("user-agent", "Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.2; .NET CLR 1.0.3705;)"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadWebpageAsXml">DownloadWebpageAsXml Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />