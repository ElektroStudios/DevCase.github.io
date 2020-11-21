# WebUtil.DownloadWebpageAsXml Method (String)
 

Downloads the source-code of an Url that points to an Html document, then transforms it to Xml.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static XDocument DownloadWebpageAsXml(
	string url
)
```

**VB**<br />
``` VB
Public Shared Function DownloadWebpageAsXml ( 
	url As String
) As XDocument
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim returnValue As XDocument

returnValue = WebUtil.DownloadWebpageAsXml(url)
```

**C++**<br />
``` C++
public:
static XDocument^ DownloadWebpageAsXml(
	String^ url
)
```

**F#**<br />
``` F#
static member DownloadWebpageAsXml : 
        url : string -> XDocument 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The Url address.</dd></dl>

#### Return Value
Type: XDocument<br />The resulting source-code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim xml As XDocument = DownloadWebpageAsXml("http://www.elhacker.net/")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadWebpageAsXml">DownloadWebpageAsXml Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />