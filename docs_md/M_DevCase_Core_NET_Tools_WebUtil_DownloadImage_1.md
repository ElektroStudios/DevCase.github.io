# WebUtil.DownloadImage Method (String, WebProxy)
 

Downloads the specified resource as a Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image DownloadImage(
	string url,
	WebProxy proxy
)
```

**VB**<br />
``` VB
Public Shared Function DownloadImage ( 
	url As String,
	proxy As WebProxy
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim proxy As WebProxy
Dim returnValue As Image

returnValue = WebUtil.DownloadImage(url, 
	proxy)
```

**C++**<br />
``` C++
public:
static Image^ DownloadImage(
	String^ url, 
	WebProxy^ proxy
)
```

**F#**<br />
``` F#
static member DownloadImage : 
        url : string * 
        proxy : WebProxy -> Image 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to download.</dd><dt>proxy</dt><dd>Type: System.Net.WebProxy<br />The proxy to use.</dd></dl>

#### Return Value
Type: Image<br />The resource Image.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim proxy As New WebProxy(Host:="myproxy address", Port:=800)
proxy.Credentials = New NetworkCredential("user", "pass")
Dim img As Image = DownloadImage("http://i.imgur.com/EkZXp16.png", proxy)
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadImage">DownloadImage Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />