# WebUtil.DownloadImage Method (String, String)
 

Downloads the specified resource as a Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image DownloadImage(
	string url,
	string userAgent
)
```

**VB**<br />
``` VB
Public Shared Function DownloadImage ( 
	url As String,
	userAgent As String
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim url As String
Dim userAgent As String
Dim returnValue As Image

returnValue = WebUtil.DownloadImage(url, 
	userAgent)
```

**C++**<br />
``` C++
public:
static Image^ DownloadImage(
	String^ url, 
	String^ userAgent
)
```

**F#**<br />
``` F#
static member DownloadImage : 
        url : string * 
        userAgent : string -> Image 

```


#### Parameters
&nbsp;<dl><dt>url</dt><dd>Type: System.String<br />The url to download.</dd><dt>userAgent</dt><dd>Type: System.String<br />Specifies a custom user-agent to perform the web request.</dd></dl>

#### Return Value
Type: Image<br />The resource Image.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img As Image = DownloadImage("http://i.imgur.com/EkZXp16.png", "Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.2; .NET CLR 1.0.3705;)")
```


## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="Overload_DevCase_Core_NET_Tools_WebUtil_DownloadImage">DownloadImage Overload</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />