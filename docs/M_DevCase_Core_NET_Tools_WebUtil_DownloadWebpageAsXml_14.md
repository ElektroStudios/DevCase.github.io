# WebUtil.DownloadWebpageAsXml Method (Uri, WebProxy)
 

Downloads the source-code of an Url that points to an Html document, then transforms it to Xml.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static XDocument DownloadWebpageAsXml(
	Uri uri,
	WebProxy proxy
)
```

**VB**<br />
``` VB
Public Shared Function DownloadWebpageAsXml ( 
	uri As Uri,
	proxy As WebProxy
) As XDocument
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim proxy As WebProxy
Dim returnValue As XDocument

returnValue = WebUtil.DownloadWebpageAsXml(uri, 
	proxy)
```

**C++**<br />
``` C++
public:
static XDocument^ DownloadWebpageAsXml(
	Uri^ uri, 
	WebProxy^ proxy
)
```

**F#**<br />
``` F#
static member DownloadWebpageAsXml : 
        uri : Uri * 
        proxy : WebProxy -> XDocument 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The Uri address.</dd><dt>proxy</dt><dd>Type: System.Net.WebProxy<br />The proxy to use.</dd></dl>

#### Return Value
Type: XDocument<br />The resulting source-code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim proxy As New WebProxy(Host:="myproxy address", Port:=800)
proxy.Credentials = New NetworkCredential("user", "pass")
Dim xml As XDocument = DownloadWebpageAsXml(New Uri("http://www.elhacker.net/"), proxy)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadWebpageAsXml">DownloadWebpageAsXml Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />