# WebUtil.DownloadWebpageAsXml Method (Uri, KeyValuePair(String, String)[])
 

Downloads the source-code of an Url that points to an Html document, then transforms it to Xml.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static XDocument DownloadWebpageAsXml(
	Uri uri,
	params KeyValuePair<string, string>[] additionalHeaders
)
```

**VB**<br />
``` VB
Public Shared Function DownloadWebpageAsXml ( 
	uri As Uri,
	ParamArray additionalHeaders As KeyValuePair(Of String, String)()
) As XDocument
```

**VB Usage**<br />
``` VB Usage
Dim uri As Uri
Dim additionalHeaders As KeyValuePair(Of String, String)()
Dim returnValue As XDocument

returnValue = WebUtil.DownloadWebpageAsXml(uri, 
	additionalHeaders)
```

**C++**<br />
``` C++
public:
static XDocument^ DownloadWebpageAsXml(
	Uri^ uri, 
	... array<KeyValuePair<String^, String^>>^ additionalHeaders
)
```

**F#**<br />
``` F#
static member DownloadWebpageAsXml : 
        uri : Uri * 
        additionalHeaders : KeyValuePair<string, string>[] -> XDocument 

```


#### Parameters
&nbsp;<dl><dt>uri</dt><dd>Type: System.Uri<br />The Uri address.</dd><dt>additionalHeaders</dt><dd>Type: System.Collections.Generic.KeyValuePair(String, String)[]<br />Specifies custom headers to perform the web request.</dd></dl>

#### Return Value
Type: XDocument<br />The resulting source-code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim xml As XDocument = DownloadWebpageAsXml(New Uri("http://www.elhacker.net/"), New KeyValuePair(Of String, String)("user-agent", "Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.2; .NET CLR 1.0.3705;)"))
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadWebpageAsXml">DownloadWebpageAsXml Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />